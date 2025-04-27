---
already_read: false
link: https://docs.vllm.ai/en/latest/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2024-05-05'
---

https://docs.vllm.ai/en/latest/
## Summary

vLLM is a high-performance library for large language model (LLM) inference and serving, designed for efficient, multi-platform deployment. 

Key Features:
- **Performance**: Optimizes serving throughput with PagedAttention, continuous batching, and fast model execution via CUDA/HIP graph. Supports various quantization methods (GPTQ, AWQ, INT4, INT8, FP8) and integrates with optimized CUDA kernels.
- **Flexibility**: Seamless integration with HuggingFace models, supports diverse hardware including NVIDIA, AMD, Intel CPUs, and various AI accelerators.
- **Serving and Inference**: Offers both offline and online serving capabilities, OpenAI-compatible APIs, and supports multi-modal inputs with distributed inference.
- **Deployment**: Compatibility with Docker, Kubernetes, Nginx, and other frameworks enhances deployment options.
- **Community and Contributions**: vLLM has evolved through community contributions and provides resources for developers to contribute and integrate models.

Documentation is structured to cover installation, examples, troubleshooting, supported models, features like quantization and LoRA adapters, and includes performance optimization tips. It also provides guidance on training, API references, and community engagement.
## Links

- [vLLM GitHub Repository](https://github.com/vllm-project/vllm) : The official GitHub repository for vLLM, containing the source code and documentation.
- [vLLM Blog Announcement](https://blog.vllm.ai/2023/06/20/vllm.html) : A blog post introducing vLLM, detailing its features and capabilities.
- [Continuous Batching in LLM Inference](https://www.anyscale.com/blog/continuous-batching-llm-inference) : A blog discussing how continuous batching improves throughput in LLM inference.
- [vLLM Paper - SOSP 2023](https://arxiv.org/abs/2210.17323) : The academic paper presenting the vLLM framework and its performance metrics.
- [vLLM Technical Report](https://arxiv.org/abs/2306.00978) : A technical report discussing further details and developments related to vLLM.

## Topics

![](topics/Library/vLLM)

![](topics/Concept/Quantization)

![](topics/Platform/Docker)

![](topics/Concept/Multimodality)

![](topics/Concept/Distributed%20Inference)

![](topics/Tool/Kubernetes)

![](topics/Concept/Reinforcement%20Learning%20from%20Human%20Feedback%20RLHF)

![](topics/Concept/Speculative%20Decoding)