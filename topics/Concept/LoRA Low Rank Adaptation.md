---
type: Concept
---

LoRA (Low-Rank Adaptation) is a technique and lightweight module used to efficiently fine-tune large language models (LLMs) by introducing small, trainable low-rank matrices. These matrices adapt the model's behavior without extensively modifying the original weights, significantly reducing computational costs, memory usage, and the number of trainable parameters. LoRA enables flexible customization of models without requiring extensive retraining, making it ideal for hardware-optimized models, edge devices, or environments with limited GPU memory. It is widely used in scenarios where resource constraints are a significant concern, as it updates only a small set of parameters while maintaining performance.