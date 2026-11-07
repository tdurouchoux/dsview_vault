---
type: Model
---

Kimi K3 is a large open-source language model with 2.8 trillion parameters, noted as the largest open-source model released to date. AirLLM enables running Kimi K3 on a single GPU with as little as 3.72GB of VRAM by streaming only the experts a token routes to, leveraging per-expert streaming and specific dependencies like `compressed-tensors`, `flash-attn`, and a CUDA 12 build of PyTorch.