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

3. **Challenges with Layers**: The plethora of layers in ML models, often optimized for specific platforms, makes it hard for compilers to convert them into other representations. New layers are constantly being invented, adding to the complexity.

4. **Non-Mathematical Operations**: Many layers involve procedural functions that are difficult to express mathematically, posing additional challenges for ML compilers.

5. **Fallback Mechanisms**: Falling back to original implementations for unsupported layers reduces the advantages of using a compiler, as it limits optimizations and portability.

6. **Python Code Compilation**: The reliance on Python glue code in many frameworks complicates porting to other environments, as parts of the model definition are held in Python rather than the compute graph.

7. **Future Directions**: The author suggests two possible futures for ML compilers: one resembling Matlab, where manual engineering is required for production deployments, and another resembling LLVM, where an intermediate representation allows for broad support across different platforms. The latter is preferred but requires changes in the training environment to make it feasible.

The post concludes with a call for innovation in the ML compiler community to develop tools that balance flexibility, performance, and portability.
## Links

- [MLIR TOSA Dialect](https://mlir.llvm.org/docs/Dialects/TOSA/) : MLIR's TOSA dialect documentation, which is an intermediate representation for machine learning models.
- [TensorFlow Lite Ops](https://www.tensorflow.org/lite/guide/ops_select) : TensorFlow Lite's supported operations, which are a subset of TensorFlow operations.
- [ONNX](https://onnx.ai/) : The Open Neural Network Exchange (ONNX) format, which is designed for interoperability between different machine learning frameworks.
- [Apache TVM](https://tvm.apache.org/) : Apache TVM is an open deep learning compiler stack for CPUs, GPUs, and specialized accelerators. It aims to close the gap between the productivity of deep learning frameworks and the performance of hardware.
- [Edge Impulse EON Compiler](https://www.edgeimpulse.com/blog/introducing-eon) : Edge Impulse's EON Compiler, which is designed to optimize machine learning models for edge devices.

## Topics

![](topics/Concept/ML%20Compilers)

![](topics/Concept/High%20Level%20Operation%20HLO)

![](topics/Concept/Intermediate%20Representation%20IR)

![](topics/Concept/Non%20Max%20Suppression)

![](topics/Concept/TensorFlow%20Lite)

![](topics/Concept/MLIR)