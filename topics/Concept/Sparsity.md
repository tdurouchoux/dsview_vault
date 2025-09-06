---
type: Concept
---

Sparsity in machine learning refers to the property of a model where only a subset of its parameters are active or contribute to the computation for a given input. This is in contrast to dense models, where all parameters are used for every input. Sparsity can significantly reduce the computational cost and memory requirements of a model, making it more efficient to train and deploy. In the context of Mixture of Experts (MoE) models, sparsity is achieved by using a gating network to route each input token to a subset of experts, ensuring that only a fraction of the model's parameters are used for each input.