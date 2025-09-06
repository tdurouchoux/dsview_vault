---
already_read: false
link: https://jiachenzhu.github.io/DyT/
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Deep_Learning
- Computer_Vision
- Natural_Language_Processing
type: Content
upload_date: '2025-03-17'
---

https://jiachenzhu.github.io/DyT/
## Summary

This paper introduces Dynamic Tanh (DyT), a simple element-wise operation that serves as a drop-in replacement for normalization layers in Transformers. DyT is inspired by the observation that layer normalization in Transformers often produces tanh-like input-output mappings. The paper demonstrates that Transformers without normalization can match or exceed the performance of their normalized counterparts using DyT, across diverse settings such as recognition, generation, supervised and self-supervised learning, and various domains like computer vision and language models. The DyT module can be implemented in a few lines of PyTorch code. Key findings include that layer normalization behaves like a scaled tanh function, with S-shaped curves in deeper layers. The paper presents a comprehensive evaluation of DyT across various architectures and tasks, showing similar or better performance compared to normalized counterparts. The paper challenges the conventional understanding that normalization layers are indispensable in modern neural networks.
## Links

- [DynamicTanh - DyT - GitHub](https://github.com/jiachenzhu/DyT) : GitHub repository for the DynamicTanh (DyT) implementation, providing code and further technical details on the project.
- [Transformers without Normalization - Paper](https://arxiv.org/abs/2503.10622) : Research paper detailing the findings and methodology behind the DynamicTanh (DyT) technique, published on arXiv.

## Topics

![](topics/Concept/Dynamic%20Tanh%20DyT)