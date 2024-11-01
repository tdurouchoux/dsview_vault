---
already_read: true
link: https://petewarden.com/2021/12/24/why-are-ml-compilers-so-hard/?utm_source=substack&utm_medium=email
read_priority: 4
source: Data Science Weekly
tags:
- MlOps
type: Content
upload_date: '2024-11-01'
---

https://petewarden.com/2021/12/24/why-are-ml-compilers-so-hard/?utm_source=substack&utm_medium=email
## Summary

The blog post discusses the complexities and challenges associated with machine learning (ML) compilers. It highlights that while various ML compilers like XLA, TVM, and MLIR exist, they are not widely adopted for running ML models. The author, drawing from personal experience rather than expertise, explains that ML compilers aim to convert models from high-level frameworks (like TensorFlow and PyTorch) into more efficient representations for better performance and portability.

Key challenges include:

1. **Diversity of Operations**: ML models consist of a vast array of operations (over 2,000 in TensorFlow), making it difficult for compilers to support all layers, as many are optimized for specific hardware.

2. **Training Constraints**: Model authors prioritize performance and often implement custom layers in low-level languages (like CUDA), complicating the compilation process.

3. **Layer Complexity**: Many layers cannot be easily expressed mathematically, requiring procedural definitions that complicate their representation in compilers.

4. **Python Dependency**: The reliance on Python for model definitions poses challenges for deployment on platforms that do not support Python, such as mobile devices.

The author suggests that to improve the situation, the ML ecosystem could evolve towards a model similar to LLVM, which uses a rich intermediate representation (IR) that supports various languages and platforms. This would require a shift in how models are expressed during training to facilitate easier compilation and deployment. The post concludes with a hopeful outlook for continued innovation in ML compilers.
## Links

1. [XLA project](https://www.tensorflow.org/xla) - A domain-specific compiler for TensorFlow that optimizes machine learning graphs.
2. [TVM](https://tvm.apache.org/) - An open-source machine learning compiler stack for CPUs, GPUs, and machine learning accelerators.
3. [MLIR](https://mlir.llvm.org/) - A compiler infrastructure that provides a common intermediate representation for various machine learning frameworks.
4. [ONNX](https://onnx.ai/) - An open format to represent machine learning models, allowing interoperability between different frameworks.
5. [PyTorch Mobile](https://pytorch.org/mobile/home/) - A framework for deploying PyTorch models on mobile devices, addressing the challenges of model portability.
## Topics

- [[topics/Concept/ML Compilers]]
- [[topics/Library/XLA]]
- [[topics/Library/TVM]]
- [[topics/Library/MLIR]]
- [[topics/Library/TensorFlow]]