---
already_read: false
link: https://docs.vllm.ai/en/latest/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-05-05'
---

https://docs.vllm.ai/en/latest/
## Summary

vLLM is a fast and easy-to-use library for LLM inference and serving, originally developed at UC Berkeley and now community-driven. Key features include:

- **Performance**: State-of-the-art serving throughput, efficient memory management with PagedAttention, continuous batching, fast model execution with CUDA/HIP graph, quantization support (GPTQ, AWQ, INT4, INT8, FP8), optimized CUDA kernels (FlashAttention, FlashInfer), and speculative decoding.
- **Flexibility**: Seamless integration with HuggingFace models, high-throughput serving with various decoding algorithms, support for tensor, pipeline, data, and expert parallelism, streaming outputs, OpenAI-compatible API server, and support for diverse hardware (NVIDIA GPUs, AMD CPUs/GPUs, Intel CPUs/GPUs, PowerPC CPUs, TPU, and plugins like Intel Gaudi, IBM Spyre, Huawei Ascend).
- **Additional Features**: Prefix caching, Multi-LoRA support, and a range of use cases from running open-source models to building applications and contributing to the project.

The documentation provides guides for users, developers, and contributors, including quickstart, user, and developer guides, as well as information on the project's roadmap and releases.
## Links

- [vLLM GitHub Repository](https://github.com/vllm-project/vllm) : The GitHub repository for vLLM, a fast and easy-to-use library for LLM inference and serving.
- [vLLM Blog](https://blog.vllm.ai) : The official blog of vLLM, featuring articles and updates about the project.
- [vLLM Announcing Blog Post](https://blog.vllm.ai/2023/06/20/vllm.html) : An introductory blog post about vLLM, focusing on PagedAttention.
- [vLLM Paper (SOSP 2023)](https://arxiv.org/abs/2306.00978) : The research paper detailing vLLM's advancements in LLM inference, presented at SOSP 2023.
- [Continuous Batching Blog Post](https://www.anyscale.com/blog/continuous-batching-llm-inference) : A blog post explaining how continuous batching enables significant improvements in LLM inference throughput and latency.

## Topics

![[topics/Library/vLLM)]]