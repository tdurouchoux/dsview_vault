---
already_read: false
link: https://jiachenzhu.github.io/DyT/
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Deep_Learning
type: Content
upload_date: '2025-03-17'
---

https://jiachenzhu.github.io/DyT/
## Summary

The paper "Transformers without Normalization" introduces Dynamic Tanh (DyT), a simple element-wise operation that serves as a replacement for normalization layers in Transformers. DyT is defined as DyT(x) = tanh(αx) and is inspired by the observation that layer normalization in Transformers often produces tanh-like, S-shaped input-output mappings. The implementation of DyT is straightforward and can be done in a few lines of PyTorch code.

Key findings include the observation that layer normalization in Transformers generates input-output mappings that resemble scaled tanh functions, with deeper layers exhibiting distinct S-shaped curves. The paper evaluates DyT across various architectures and tasks, including vision, language, speech, and DNA sequence modeling, demonstrating that Transformers with DyT can match or exceed the performance of their normalized counterparts without extensive hyperparameter tuning. This challenges the conventional understanding of the indispensability of normalization layers in modern neural networks. The paper is set to be presented at CVPR 2025, with corresponding code and additional resources available for further exploration.
## Links

- [DynamicTanh - DyT - GitHub](https://github.com/jiachenzhu/DyT) : GitHub repository for the DynamicTanh (DyT) implementation, providing code and further technical details about the project.
- [Transformers without Normalization - Paper](https://arxiv.org/abs/2503.10622) : Research paper detailing the findings and methodology behind the DynamicTanh (DyT) technique, explaining how Transformers without normalization can achieve similar or better performance.

## Topics

![[topics/Concept/Dynamic Tanh DyT]]

![[topics/Model/Vision Transformer]]

![[topics/Model/wav2vec 2 0]]

![[topics/Model/LLaMA]]

![[topics/Model/Diffusion Transformer DiT]]