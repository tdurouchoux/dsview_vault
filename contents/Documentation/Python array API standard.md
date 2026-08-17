---
already_read: false
link: https://data-apis.org/array-api/latest/purpose_and_scope.html
read_priority: 4
relevance: 0
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-08-17'
---

https://data-apis.org/array-api/latest/purpose_and_scope.html

## Summary

The Python Array API Standard 2025.12 aims to unify the fragmented landscape of multidimensional array libraries (e.g., NumPy, PyTorch, JAX) by defining a common API for core array operations, enabling interoperability and code reuse across libraries.

**Purpose & Motivation**
- Addresses fragmentation among Python array libraries (NumPy, TensorFlow, PyTorch, JAX, etc.) by standardizing common functionality.
- Avoids forcing a single existing API (e.g., NumPy) as the standard due to valid differences in design (e.g., non-CPU devices, JIT compilation).
- Goals: enable cross-library code reuse, reduce learning curves, and provide a reference for new array libraries.

**Scope**
- **In scope**: Function names/signatures, semantics (including precision, dtype handling), casting rules, broadcasting, indexing, device support, and data interchange protocols.
- **Out of scope**: Implementations, execution semantics (e.g., parallelism, eager vs. lazy evaluation), non-Python APIs (Cython/NumPy C APIs), specific dtypes (bfloat16, datetime, strings), I/O, error handling, ufuncs/gufuncs, and mixed-library operations.
- **Non-goals**: Merging libraries, runtime switching between backends, or mixing libraries in function calls.

**Key Technical Details**
- Standardizes core functionality present in most libraries, informed by usage data and consistency needs (e.g., operator equivalents).
- Compliance checked via `__array_namespace__()` method on array objects, with optional `api_version` parameter.
- Discoverability of conforming implementations via `importlib.metadata` entry points (group: `array_api`, name: package name).
- Conforming implementations must support all specified functions/arguments but may add extra features.

**Adoption & Implementation**
- Libraries should expose the standard-compliant API in a new namespace (e.g., `package_name.array_api`).
- Recommended compliance check: `hasattr(x, '__array_namespace__')`.
- No reference implementation provided; conformance verified via test suites.

**Stakeholders**
- Direct: Maintainers of Python array libraries (NumPy, PyTorch, JAX, etc.).
- Indirect: Array-consuming libraries (Pandas, SciPy, scikit-learn), compilers (Numba, Cython), and end users.

**Historical Context**
- Inspired by NumPy’s role in resolving earlier fragmentation (2005), but modern needs (new hardware, deep learning) require a coordinated standard.
- Developed by the Consortium for Python Data API Standards (formed May 2020).

## Links

- [NumPy](https://numpy.org) : The foundational library for numerical computing in Python, often used as a reference for array operations and API design in the array API standard.
- [PyTorch](https://pytorch.org/) : A popular deep learning framework that is one of the key stakeholders in the array API standard, providing tensor operations and GPU acceleration.
- [TensorFlow](https://www.tensorflow.org/) : A widely used machine learning framework that supports tensor operations and is a stakeholder in the array API standard.
- [JAX](https://github.com/google/jax) : A high-performance numerical computing library with automatic differentiation and GPU/TPU support, relevant for array API standard compliance.
- [Apache Arrow](https://arrow.apache.org/) : A cross-language development platform for in-memory data that includes array-like structures, relevant for data interchange in the array API standard.


## Topics

![[topics/Platform/Python array API standard]]

![[topics/Library/TensorFlow]]

![[topics/Library/MXNet]]

![[topics/Library/xarray]]

![[topics/Concept/Array API compliance]]

![[topics/Library/NumPy]]

![[topics/Library/PyTorch]]

![[topics/Library/JAX]]

![[topics/Library/Dask]]

![[topics/Library/CuPy]]