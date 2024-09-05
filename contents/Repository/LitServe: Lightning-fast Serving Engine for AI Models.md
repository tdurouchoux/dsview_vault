---
already_read: true
link: https://github.com/Lightning-AI/LitServe
read_priority: 1
tags:
- MlOps
- Deep_Learning
- Python
type: Content
upload_date: '2024-09-04'
---

https://github.com/Lightning-AI/LitServe
## Summary

LitServe is a high-performance serving engine for AI models, built on FastAPI, designed for flexibility and enterprise-scale applications. Key features include:

- **Performance**: At least 2x faster than standard FastAPI, with optimizations for batching, streaming, and GPU autoscaling.
- **Model Support**: Compatible with various frameworks like PyTorch, JAX, and TensorFlow, allowing users to bring their own models.
- **Ease of Use**: Simplifies the process of serving AI models, enabling the creation of complex systems with multiple models.
- **Hosting Options**: Can be self-hosted or managed through Lightning Studios, offering scalability and security.
- **Community and Contributions**: Open-source with an active community for support and development.

LitServe is suitable for a wide range of AI applications, including LLMs, vision, audio, and classical machine learning tasks. It emphasizes enterprise-level features and performance optimizations for AI workloads.
## Links

1. [LitServe Documentation](https://lightning.ai/docs/litserve) - Comprehensive guide on how to use LitServe for serving AI models, including installation, features, and examples.
2. [LitGPT](https://github.com/Lightning-AI/litgpt?tab=readme-ov-file#deploy-an-llm) - A tool built on LitServe specifically for serving large language models (LLMs).
3. [FastAPI](https://fastapi.tiangolo.com/) - The web framework on which LitServe is built, known for its speed and ease of use in building APIs.
4. [OpenAPI](https://www.openapis.org/) - Specification for building APIs that LitServe is compliant with, allowing for better integration and documentation.
5. [GPU Autoscaling](https://lightning.ai/docs/litserve/features/gpu-inference) - Feature of LitServe that allows for automatic scaling of GPU resources based on demand, enhancing performance for AI model serving.
## Topics

- [[topics/Library/LitServe]]
- [[topics/Concept/API]]
- [[topics/Concept/Serving]]
- [[topics/Concept/GPU Autoscaling]]
- [[topics/Concept/Batching]]