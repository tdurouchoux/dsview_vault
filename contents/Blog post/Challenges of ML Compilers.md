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

The blog post discusses the complexities and challenges associated with machine learning (ML) compilers. It highlights the evolution of ML compilers like XLA, TVM, and MLIR, which aim to optimize the performance of ML models but are not yet widely adopted. 

Key points include:

- **Definition and Purpose**: ML compilers convert models from high-level frameworks (like TensorFlow and PyTorch) into optimized representations for better performance and portability.

- **Challenges**: The vast and growing number of operations in deep learning (e.g., TensorFlow has over 2,000 operations) complicates the compilation process. Many ML compilers only support a subset of these operations, leading to user frustration.

- **Differences from Procedural Compilers**: Unlike traditional compilers, ML compilers deal with a dynamic set of layers and operations, making it difficult to maintain a manageable representation.

- **Layer Complexity**: Many layers in ML models are not easily expressible mathematically, leading to reliance on procedural code, which complicates optimization and portability.

- **Fallback Mechanisms**: Relying on original C++ implementations for unsupported layers undermines the benefits of using a compiler, as it limits optimization opportunities.

- **Python Integration**: The use of Python in model definitions poses challenges for compilation, especially on platforms that do not support Python.

- **Future Directions**: The author envisions two potential futures for ML compilers: one resembling Matlab, where manual conversion is common, and another akin to LLVM, which would utilize a rich intermediate representation to support various models and frameworks.

The post concludes with a call for innovation in the ML compiler community to create tools that balance flexibility for researchers with the need for optimized, portable representations.
## Links

1. [XLA Architecture](https://www.tensorflow.org/xla/architecture) - Overview of the XLA (Accelerated Linear Algebra) compiler and its architecture for optimizing TensorFlow computations.
2. [ONNX](https://onnx.ai/) - Open Neural Network Exchange, a format for deep learning models that facilitates interoperability between different frameworks.
3. [MLIR TOSA Dialect](https://mlir.llvm.org/docs/Dialects/TOSA/) - Documentation on the TOSA (Tensor Operator Set Architecture) dialect in MLIR, which aims to provide a common intermediate representation for machine learning.
4. [TVM](https://tvm.apache.org/) - An open-source machine learning compiler stack that aims to enable efficient deployment of deep learning models across various hardware platforms.
5. [TensorFlow Function API](https://www.tensorflow.org/api_docs/python/tf/function) - Documentation on TensorFlow's `tf.function`, which allows for compiling Python functions into TensorFlow graphs for performance optimization.
## Topics

![](topics/Concept/ML%20Compilers)

![](topics/Library/XLA)

![](topics/Library/TVM)

![](topics/Library/MLIR)

![](topics/Library/TensorFlow)