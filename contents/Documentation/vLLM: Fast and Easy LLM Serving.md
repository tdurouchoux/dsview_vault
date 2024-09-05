---
already_read: false
link: https://docs.vllm.ai/en/latest/
read_priority: 1
source: null
tags:
- Large_Language_Model
- Deep_Learning
type: Content
upload_date: '2024-05-05'
---

https://docs.vllm.ai/en/latest/
## Summary

vLLM is a library designed for efficient large language model (LLM) inference and serving, emphasizing speed, flexibility, and ease of use. Key features include:

- **Performance**: High throughput with state-of-the-art serving capabilities, efficient memory management via PagedAttention, continuous batching, and fast model execution using CUDA/HIP. Supports various quantization methods (GPTQ, AWQ, INT4, INT8, FP8) and speculative decoding.

- **Flexibility**: Integrates seamlessly with HuggingFace models, supports multiple decoding algorithms, and offers tensor and pipeline parallelism for distributed inference. It is compatible with a range of hardware including NVIDIA and AMD GPUs, Intel CPUs, TPUs, and AWS Neuron.

- **Installation and Deployment**: Provides detailed installation instructions for various platforms (ROCm, OpenVINO, CPU, TPU, etc.) and deployment options using Docker, KServe, and other frameworks.

- **Model Support**: Includes support for adding new models, enabling multimodal inputs, and using LoRA adapters.

- **Quantization and Caching**: Features automatic prefix caching and various quantization techniques to optimize performance.

- **Community and Documentation**: Offers extensive documentation, FAQs, and community engagement through meetups.

Overall, vLLM aims to provide a robust solution for LLM serving with a focus on performance and user-friendliness.
## Links

1. [GPTQ](https://arxiv.org/abs/2210.17323) - A paper discussing the GPTQ quantization method for neural networks, relevant for understanding quantization techniques in LLMs.
2. [AWQ](https://arxiv.org/abs/2306.00978) - A research paper on the AWQ quantization approach, providing insights into advanced quantization strategies for model efficiency.
3. [vLLM paper](https://arxiv.org/abs/2309.06180) - The official paper detailing the vLLM framework, its architecture, and performance benchmarks.
4. [How continuous batching enables 23x throughput in LLM inference while reducing p50 latency](https://www.anyscale.com/blog/continuous-batching-llm-inference) - A blog post explaining the benefits of continuous batching in LLM inference, crucial for optimizing performance.
5. [vLLM announcing blog post](https://vllm.ai) - An introductory blog post about vLLM, outlining its features and capabilities in LLM serving.
## Topics

- [[topics/Library/vLLM]]
- [[topics/Concept/PagedAttention]]
- [[topics/Concept/Quantization]]
- [[topics/Platform/OpenAI Compatible Server]]
- [[topics/Concept/Multi-modality in Vision and Language Models]]