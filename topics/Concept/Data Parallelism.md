---
type: Concept
---

Data parallelism is a technique in distributed training where the same model is trained on different subsets of data across multiple devices. Each device computes gradients locally and then aggregates them to update the model parameters, enabling faster and more efficient training.