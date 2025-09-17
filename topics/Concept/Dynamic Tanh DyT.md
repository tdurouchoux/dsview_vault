---
type: Concept
---

Dynamic Tanh (DyT) is an element-wise operation defined as DyT(x) = tanh(αx), introduced as a replacement for normalization layers in Transformers. It is inspired by the observation that layer normalization in Transformers often produces tanh-like, S-shaped input-output mappings. DyT aims to achieve similar or better performance compared to normalized Transformers without the need for extensive hyperparameter tuning.