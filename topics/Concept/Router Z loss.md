---
type: Concept
---

Router Z-loss is a technique used to stabilize the training of Mixture of Experts (MoE) models by penalizing large logits entering the gating network. This loss encourages smaller absolute magnitudes of values, reducing roundoff errors and improving the stability of the training process, especially for exponential functions like the gating mechanism.