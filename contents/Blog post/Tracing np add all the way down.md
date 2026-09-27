---
already_read: false
link: https://blog.veitheller.de/numpy.html
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Development_tool
type: Content
upload_date: '2026-09-27'
---

https://blog.veitheller.de/numpy.html

## Summary

np.add(a, b) is a deceptively simple call that triggers a deep, optimized machinery in NumPy to perform element-wise addition efficiently.

**Overview**
- np.add is a numpy.ufunc object, bundling inner loops for each supported type signature (e.g., dd->d for float64).
- The call stack: Python entry → C argument parsing → override check → type promotion/dispatch → iteration strategy → SIMD kernel.

**Key Technical Path**
- **Entry & Parsing**: np.add calls ufunc_generic_fastcall (C), which parses args and checks for __array_ufunc__ overrides (e.g., Dask/CuPy).
- **Dispatch**: Resolves input dtypes to a loop (e.g., dd->d) via promotion, caching results for future calls.
- **Loop Selection**: Uses legacy PyUFuncGenericFunction for built-in types, wrapped in modern PyArrayMethodObject.
- **Iteration Strategy**: Trivial loop (single call) for contiguous/aligned arrays; NpyIter for broadcasting, strides, or overlaps.
- **SIMD Kernel**: Template-generated (e.g., DOUBLE_add) with CPU-specific optimizations (AVX2, NEON), falling back to scalar loop for misaligned data.

**Performance Insights**
- Contiguous arrays use SIMD-accelerated loops; strided arrays (e.g., a[::2]) fall back to scalar loops, causing ~2.6x slowdown.
- GIL is released during computation; FP status flags are checked for warnings (e.g., overflow).

**Implementation Details**
- Loops are generated from templates (e.g., loops_arithm_fp.dispatch.c.src) and compiled per CPU feature set.
- Dispatch uses runtime CPU checks (e.g., NPY_CPU_DISPATCH_CALL) to select the best variant (e.g., AVX2 vs. baseline).
- Legacy code (e.g., PyUFunc_DefaultLegacyInnerLoopSelector) remains core but is being refactored for free-threaded Python.

**Notable Observations**
- NumPy’s internals retain decades-old designs (e.g., ufunc types table) while adding modern layers (ArrayMethod, SIMD dispatch).
- Recent optimizations (e.g., caching loop selection) target free-threaded Python compatibility.

## Links

- [NEP 13: Ufunc Overrides Protocol](https://numpy.org/neps/nep-0013-ufunc-overrides.html) : This NEP (NumPy Enhancement Proposal) describes the __array_ufunc__ protocol, which allows external libraries to override NumPy's default ufunc behavior. It is directly referenced in the blog post as the mechanism enabling libraries like Dask and CuPy to intercept and handle ufunc calls.
- [NEP 15: Merge of multiarray and umath Modules](https://numpy.org/neps/nep-0015-merge-multiarray-umath.html) : This NEP explains the historical separation and later merging of NumPy's multiarray and umath C modules. It provides context for the internal structure of NumPy's ufunc machinery, as mentioned in the blog post.
- [NEP 18: Array Function Protocol](https://numpy.org/neps/nep-0018-array-function-protocol.html) : This NEP describes the __array_function__ protocol, which is analogous to __array_ufunc__ but for non-ufunc functions like np.concatenate. The blog post clarifies the distinction between these protocols in the context of ufuncs.
- [NEP 43: Extensible Ufuncs](https://numpy.org/neps/nep-0043-extensible-ufuncs.html) : This NEP introduces the PyArrayMethodObject, a modern representation of ufunc implementations for concrete DTypes. It is central to the blog post's discussion of how NumPy dispatches and executes ufuncs like np.add.
- [NumPy Source: Dispatching and Promotion in Ufuncs](https://github.com/numpy/numpy/blob/v2.5.2/numpy/_core/src/umath/dispatching.cpp) : This source file contains the implementation of the dispatching and promotion logic for ufuncs, as described in the blog post. It details how NumPy selects the appropriate loop for a given operation and DType combination.


## Topics

![[topics/Concept/Universal Function ufunc]]

![[topics/Concept/Type Promotion and Dispatch]]

![[topics/Concept/NpyIter]]

![[topics/Concept/SIMD Optimization]]

![[topics/Concept/__array_ufunc__ Protocol]]

![[topics/Concept/ArrayMethod]]

![[topics/Concept/CPU Dispatch]]

![[topics/Library/NumPy]]