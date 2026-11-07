---
type: Concept
---

Layer-wise streaming is a technique used by AirLLM to enable the execution of large language models on hardware with limited VRAM. Instead of loading the entire model into memory, AirLLM streams one layer at a time from disk to the GPU, keeping only the current layer resident during computation. This approach reduces VRAM requirements to depend primarily on the size of individual layers rather than the total model size, making it feasible to run models with hundreds of billions of parameters on consumer-grade GPUs.