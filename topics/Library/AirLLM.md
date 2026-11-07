---
type: Library
---

AirLLM is a Python library designed to enable efficient inference and training of large language models (LLMs) on low-end hardware with limited VRAM. It achieves this by streaming model layers one at a time from disk to the GPU, keeping only the necessary layers resident during computation. Key features include model compression (block-wise quantization) for faster inference, support for training large models on small GPUs by streaming frozen weights and keeping adapters on the GPU, and compatibility with a wide range of popular open LLMs (e.g., Llama, Qwen, DeepSeek, Mistral). AirLLM also supports configurations like 4-bit/8-bit compression, prefetching for overlapping model loading and compute, and layer-wise model splitting for disk space efficiency.