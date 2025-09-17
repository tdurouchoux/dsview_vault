---
type: Concept
---

Data parallelism is a technique in distributed training where different subsets of the data are processed simultaneously across multiple devices. Each device has a copy of the model, and gradients are synchronized periodically to update the model weights.