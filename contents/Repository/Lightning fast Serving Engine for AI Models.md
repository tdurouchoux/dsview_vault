---
already_read: true
link: https://github.com/Lightning-AI/LitServe
read_priority: 1
source: null
tags:
- MlOps
- Deep_Learning
type: Content
upload_date: '2024-09-04'
---

https://github.com/Lightning-AI/LitServe
## Summary

LitServe is a high-performance serving engine for AI models, designed to be flexible and scalable for enterprise use. Built on FastAPI, it enhances model serving with features like batching, streaming, and GPU autoscaling, achieving at least 2x faster performance than standard FastAPI.

Key features include:
- Support for various AI models (LLMs, vision, etc.)
- Easy integration with frameworks like PyTorch, JAX, and TensorFlow
- Ability to build compound AI systems with multiple models
- Options for self-hosting or fully managed deployment via Lightning Studios
- OpenAPI compliance and support for Dockerization

The setup process involves defining an API with a simple class structure, and the server can be run with minimal configuration. LitServe is optimized for AI workloads, making it suitable for tasks like image classification, text embedding, and more. It also offers community support and contributions are welcome.
## Links

1. [LitServe Documentation](https://lightning.ai/docs/litserve) - Comprehensive guide on how to use LitServe for serving AI models.
2. [Deploy a Multi-Modal LLM with Pixtral](https://lightning.ai/lightning-ai/studios/deploy-a-multi-modal-llm-with-pixtral) - Example of deploying a multi-modal large language model using LitServe.
3. [Deploy Both PyTorch and TensorFlow in a Single API](https://lightning.ai/lightning-ai/studios/deploy-both-pytorch-and-tensorflow-in-a-single-api) - Guide on how to serve models from both frameworks using LitServe.
4. [GPU Inference Features](https://lightning.ai/docs/litserve/features/gpu-inference) - Details on how to utilize GPU capabilities for inference with LitServe.
5. [Speed Up Serving by 200x](https://lightning.ai/docs/litserve/home/speed-up-serving-by-200x) - Insights on optimizing the performance of model serving with LitServe.
## Topics

![](topics/Product/LitServe)

![](topics/Concept/FastAPI)

![](topics/Concept/GPU%20Autoscaling)

![](topics/Concept/Batching)

![](topics/Concept/Streaming%20and%20Streaming%20API)