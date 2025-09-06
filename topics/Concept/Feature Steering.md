---
type: Concept
---

Feature steering is a technique used to modify the activations of a model during a forward pass to influence downstream behavior. This involves decomposing the residual stream activity into the sum of two components, the SAE reconstruction and the reconstruction error, and then replacing the SAE reconstruction with a modified reconstruction in which the activity of a specific feature is clamped to a specific value. This allows for the study of the causal effects of features on model behavior, providing insights into how features influence the model's outputs and helping to understand the model's internal representations and computations.