---
already_read: true
link: https://petewarden.com/2021/12/24/why-are-ml-compilers-so-hard/
read_priority: 4
relevance: 0
source: Data Science Weekly
tags:
- Data_Engineering
type: Content
upload_date: '2024-11-01'
---

https://petewarden.com/2021/12/24/why-are-ml-compilers-so-hard/
## Summary

The post discusses the complexities and challenges associated with machine learning (ML) compilers, emphasizing their role in optimizing the execution of deep learning models across various platforms. Key points include:

- **Definition and Purpose**: ML compilers transform models from major frameworks (like TensorFlow and PyTorch) into more efficient representations for improved performance and portability. They often utilize domain-specific compilation techniques.

- **Challenges**: ML compilers face difficulties due to the vast, ever-expanding set of operations in deep learning, with TensorFlow possessing over 2,000 operations. This diversity contrasts with procedural languages, which maintain a limited set of primitives. Many model authors prioritize performance over formal representation, complicating compilation efforts.

- **Layer Complexity**: The post highlights how ML graphs consist of layers optimized for performance, often leading to a situation where many compilers support only a subset of these layers. This creates confusion for model developers who may be unaware of operational constraints related to compilation.

- **Need for Intermediate Representation (IR)**: The author advocates for a rich intermediate representation similar to LLVM for ML, which could help unify various model representations and facilitate cross-platform compatibility. The need for this representation stems from the necessity to balance flexibility for researchers with portability and performance requirements.

- **Future Directions**: The author proposes two possible futures for ML compilers: one resembling a MATLAB-like ecosystem, where manual engineering is needed for production deployments, and another more integrated approach like LLVM that allows for better encoding of models for various platforms.

Progress depends on cultivating a training environment that supports model portability and performance while allowing for ongoing research and experimentation. The author expresses hope for continued innovation in the ML compiler landscape.
## Links

- [TensorFlow Lite Guide - Operations Selection](https://www.tensorflow.org/lite/guide/ops_select) : Official documentation on selecting operations for TensorFlow Lite models.
- [XLA Architecture](https://www.tensorflow.org/xla/architecture) : Detailed information about the architecture of XLA (Accelerated Linear Algebra), TensorFlow's domain-specific compiler.
- [ONNX - Open Neural Network Exchange](https://onnx.ai/) : An open-source format for AI models, which is useful for interoperability between different machine learning frameworks.
- [TVM - An Open Deep Learning Compiler Stack](https://tvm.apache.org/) : An open-source deep learning compiler stack that enables efficient model deployment on a variety of hardware.
- [MLIR - Multi-Level Intermediate Representation](https://mlir.llvm.org/) : Documents on MLIR, a project aimed at building reusable and extensible compiler infrastructure.

## Topics

![](topics/Concept/ML%20Compilers)

![](topics/Library/XLA%20Accelerated%20Linear%20Algebra)

![](topics/Library/MLIR%20Multi%20Level%20Intermediate%20Representation)

![](topics/Concept/Intermediate%20Representation%20IR)

![](topics/Concept/Domain%20Specific%20Compilers)

![](topics/Tool/TensorFlow%20Lite)