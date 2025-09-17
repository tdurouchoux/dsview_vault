---
type: Concept
---

Attribution is a method used to estimate the causal effect of a feature's activation on the model's output. In the context of interpretability, attribution involves computing the gradient of the difference between an output logit of interest and a baseline token with respect to the residual stream activations. This method helps in identifying the features that are most relevant to a specific output and in understanding the model's intermediate computations. Attribution is a powerful tool for analyzing the model's behavior and for steering the model towards desired outputs.