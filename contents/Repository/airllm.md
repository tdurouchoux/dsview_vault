---
already_read: true
link: https://github.com/lyogavin/airllm
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Large_Language_Model
- Model_evaluation
type: Content
upload_date: '2026-11-07'
---

https://github.com/lyogavin/airllm

## Summary

AirLLM enables running and training massive LLMs (up to 2.8T parameters) on consumer GPUs with minimal VRAM by streaming model layers from disk, avoiding quantization or distillation.

**Key capabilities**
- Runs **Kimi K3 (2.8T)** in **3.72GB**, **Qwen3.8-Flash-Next (125B)** in **5.95GB**, **DeepSeek-V3 (671B)** in **~12GB**, **Llama3.1 405B** in **~8GB**
- Supports **training** huge models on small VRAM (e.g., **Qwen3.8-Flash-Next (125B)** under **6GB**, **Qwen3.8-27B** in **~2GB**)
- Works with **Llama, Qwen, DeepSeek, Mistral, Phi, Gemma, ChatGLM, Baichuan, InternLM, Yi, Kimi K3** via `AutoModel.from_pretrained()`
- **Block-wise quantization** (4bit/8bit) for **3x inference speedup** with negligible accuracy loss

**Technical approach**
- Streams **one layer at a time** to GPU, reducing VRAM dependency on layer size rather than total model size
- **Prefetching** overlaps model loading and compute for **10% speed improvement**
- **Model compression** via weight-only quantization (no activation quantization) to minimize disk I/O bottlenecks
- **Delete original model files** option to save disk space after layer-wise splitting

**Usage**
- Install: `pip install airllm`
- Inference: `model = AutoModel.from_pretrained("Qwen/Qwen3-32B")` (same API for all supported models)
- Training: `AirLLMLoRAQwen4Exp` for Qwen3.8-Flash-Next, `AirLLMLoRA` for Qwen3.8-27B
- Configurations: `compression` (4bit/8bit), `prefetching`, `layer_shards_saving_path`, `hf_token`, `delete_original`

**Limitations**
- MacOS: Only **Apple Silicon** and **Llama-style models** supported
- Requires **CUDA 12** for some models (e.g., Kimi K3)
- Disk space-intensive during initial model splitting (can hit `MetadataIncompleteBuffer` errors if disk is full)

## Links

- [Block-wise Quantization Paper (arXiv)](https://arxiv.org/abs/2212.09720) : A research paper discussing block-wise quantization-based model compression, which is the technique used by AirLLM to achieve up to 3x inference speed improvement with minimal accuracy loss.
- [bitsandbytes GitHub Repository](https://github.com/TimDettmers/bitsandbytes) : The official repository for bitsandbytes, a library required for enabling model compression in AirLLM (e.g., 4-bit or 8-bit quantization).
- [Hugging Face Datasets Cache Documentation](https://huggingface.co/docs/datasets/cache) : Documentation explaining how to manage the Hugging Face datasets cache, which is relevant for resolving disk space issues during model splitting in AirLLM.
- [AirLLM PyPI Package](https://pypi.org/project/airllm/) : The Python Package Index (PyPI) page for AirLLM, where users can install the library and access its documentation.
- [MLX GitHub Repository](https://github.com/ml-explore/mlx?tab=readme-ov-file#installation) : The official repository for MLX, a machine learning framework required for running AirLLM on MacOS (Apple Silicon).


## Topics

![[topics/Library/AirLLM]]

![[topics/Model/Kimi K3]]

![[topics/Model/Qwen3 8 Flash Next]]

![[topics/Model/Qwen3]]

![[topics/Model/DeepSeek V3]]

![[topics/Model/LLaMA]]

![[topics/Concept/Layer wise Streaming]]

![[topics/Concept/Model Compression]]