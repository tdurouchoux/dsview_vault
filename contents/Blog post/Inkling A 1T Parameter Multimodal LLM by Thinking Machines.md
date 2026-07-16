---
already_read: true
link: https://huggingface.co/blog/thinkingmachines-inkling
read_priority: 0
relevance: 5
source: youtube
tags:
- Large_Language_Model
type: Content
upload_date: '2026-07-16'
---

https://huggingface.co/blog/thinkingmachines-inkling
## Summary

Inkling by Thinking Machines is a groundbreaking 1T-parameter multimodal LLM supporting text, image, and audio inputs with a 1M context window. Key technical highlights:

**Architecture**:
- Decoder-only Mixture-of-Experts (MoE) model (975B total, 41B active params)
- Relative attention instead of RoPE, hybrid attention (5:1 sliding window/global)
- Short 1D convolution (SConv) for local representation
- Simple hierarchical MLP patchifier for vision and mel spectrogram processing for audio

**Inference**:
- Day-0 support in Transformers, SGLang, vLLM
- BF16 (2TB VRAM) and NVFP4 (600GB VRAM) variants
- Local deployment via llama.cpp (1-bit quant) or Unsloth
- Hugging Face Inference Providers for serverless access

**Use Cases**:
- Agentic coding (Pi integration)
- Multi-Token Prediction (MTP) for faster inference
- Strong multimodal reasoning (vision/audio benchmarks)
- Post-training via Tinker/RL (ECHO algorithm)

**Benchmark Highlights**:
- Top-tier performance in reasoning (HLE, AIME 2026), agentic tasks (SWEBench), and multimodal benchmarks (MMMU Pro, MMAU)
- Superior safety scores (FORTRESS, StrongREJECT)

**Key Takeaway**: Inkling sets new standards for open multimodal LLMs with massive context support, efficient MoE architecture, and strong cross-modal reasoning capabilities.
## Links

- [Inkling Model on Hugging Face](https://huggingface.co/thinkingmachines/Inkling) : The official Hugging Face repository for the Inkling model by Thinking Machines. This link provides access to the model card, architecture details, and downloadable checkpoints for inference.
- [Big Bench Audio Dataset](https://huggingface.co/datasets/ArtificialAnalysis/big_bench_audio) : A dataset used for evaluating audio reasoning capabilities in models like Inkling. It contains logical statements and questions designed for speech-to-speech reasoning tasks.
- [GlobeAudio Dataset](https://huggingface.co/datasets/iNLP-Lab/GlobeAudio) : A multilingual audio dataset used to evaluate Inkling's audio reasoning capabilities. It includes audio files and questions in languages like Russian and Chinese.
- [Tinker Echo Demo for Post-Training](https://github.com/huggingface/OpenEnv/blob/main/examples/echo_world_model/backends/tinker_echo_demo.py) : A Python script demonstrating how to use the Tinker tool for post-training Inkling with reinforcement learning. This script is part of the OpenEnv framework and showcases the ECHO algorithm for training a model to predict environment tokens.
- [GOLD Algorithm for Knowledge Distillation](https://github.com/huggingface/trl/blob/main/examples/scripts/gold.py) : A script implementing the GOLD algorithm for knowledge distillation, which can be used to distill knowledge from Inkling to smaller models. This is useful for improving the performance of on-device models. Part of the Transformers Reinforcement Learning (TRL) library.

## Topics

![[topics/Model/Inkling]]

![[topics/Concept/Mixture of Experts MoE]]

![[topics/Concept/Relative Attention]]

![[topics/Concept/Hybrid Attention]]

![[topics/Concept/Short Convolution SConv]]

![[topics/Tool/tinker]]

![[topics/Dataset/BigBenchAudio]]

![[topics/Dataset/GlobeAudio]]

![[topics/Concept/Multi Token Prediction MTP]]

![[topics/Concept/Speculative Decoding]]