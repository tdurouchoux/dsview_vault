---
type: Model
---

Qwen3.8-Flash-Next is a 125B parameter Mixture-of-Experts (MoE) model from the Qwen family, featuring a ~51B n-gram embedding. It is designed for efficient inference and training on limited hardware. AirLLM supports running this model on a single GPU with ~5.95GB VRAM (measured on an RTX 4090) and training it under 6GB VRAM by streaming frozen weights one layer at a time and keeping adapters on the GPU. The model requires a custom `transformers` build with in-tree `qwen4_exp` and ~360GB of checkpoint disk space.