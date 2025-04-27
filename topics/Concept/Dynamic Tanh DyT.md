---
date: '2025-03-17'
type: Concept
---

Dynamic Tanh (DyT) is a proposed layer in neural network architectures, specifically transformers, that acts as a replacement for traditional normalization layers such as Layer Norm or RMSNorm. DyT introduces an element-wise operation defined as DyT(x) = tanh(αx), adjusting the input using a learnable scaling factor (α). This technique allows transformers to maintain or exceed performance levels compared to those with normalization layers, suggesting that normalization is not as crucial as previously believed in certain contexts.