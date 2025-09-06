---
type: Concept
---

Router Z-loss is a technique used to stabilize the training of Mixture of Experts (MoE) models by penalizing large logits entering the gating network. By encouraging the absolute magnitude of the values to be smaller, router Z-loss helps to reduce roundoff errors, which can be particularly impactful for exponential functions such as the gating function. This stabilization method improves the training stability of sparse models without degrading their quality, making it a valuable tool for optimizing the performance of MoE models.