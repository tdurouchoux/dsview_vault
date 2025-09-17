---
already_read: true
link: https://petewarden.com/2021/12/24/why-are-ml-compilers-so-hard/
read_priority: 4
relevance: 0
source: Data Science Weekly
tags:
- MlOps
- Development_tool
type: Content
upload_date: '2024-11-01'
---

https://petewarden.com/2021/12/24/why-are-ml-compilers-so-hard/
## Summary

The blog post discusses the challenges faced by machine learning (ML) compilers and why they are not as widely adopted as traditional procedural compilers. The author, Pete Warden, highlights several key points:

1. **Definition and Scope of ML Compilers**: ML compilers convert models defined in Python using major training frameworks into different forms for better performance or portability. However, the term "compiler" is often misleading as many tools generate intermediate representations rather than final code.

2. **Differences from Procedural Compilers**: ML computation graphs consist of a large, ever-growing set of layers, unlike procedural languages with a small number of core primitives. This makes it difficult for ML compilers to support all operations, leading to subsets of supported layers.

3. **Challenges with Layers**: The plethora of layers in ML models, including those defined for performance reasons, makes it hard for compilers to convert them into other representations. New layers are constantly being invented, adding to the complexity.

4. **Fallbacks and Portability**: Falling back to original CPU implementations for unsupported layers reduces the advantages of using a compiler, as it limits optimizations and portability. Porting layers often means porting the entire training framework, which is resource-intensive.

5. **Python Code in Models**: Many frameworks rely on Python glue code, making it difficult to port models to environments that don't support Python, such as mobile platforms and GPUs.

6. **Future Directions**: The author suggests two possible futures for the ML ecosystem: one resembling Matlab, where manual engineering is required for production deployments, and another resembling LLVM, where a rich intermediate representation allows for broad support. The author advocates for changing the training environment to produce more manageable representations from the start.

The post concludes with a call for continued innovation in the ML compiler community to address these challenges.
## Links

- [TensorFlow XLA Architecture](https://www.tensorflow.org/xla/architecture) : Explanation of the architecture behind XLA (Accelerated Linear Algebra), a domain-specific compiler for machine learning graphs integrated into TensorFlow.
- [MLIR (Multi-Level Intermediate Representation)](https://mlir.llvm.org/) : Information about MLIR, a compiler infrastructure designed for reusable and extensible compiler construction.
- [ONNX (Open Neural Network Exchange)](https://onnx.ai/) : Details about ONNX, an open format built to represent machine learning models, enabling interoperability between different frameworks, runtimes, and hardware platforms.

## Topics

![](topics/Concept/ML%20Compilers)

![](topics/Concept/High%20Level%20Operations%20HLO)

![](topics/Concept/Intermediate%20Representation%20IR)

![](topics/Concept/Non%20Max%20Suppression)

![](topics/Concept/Machine%20Learning%20Compilation)

![](topics/Concept/Model%20Optimization)