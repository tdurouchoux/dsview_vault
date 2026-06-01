---
already_read: true
link: https://github.com/zai-org/GLM-OCR
read_priority: 0
relevance: 4
source: null
tags:
- Computer_Vision
type: Content
upload_date: '2026-06-01'
---

https://github.com/zai-org/GLM-OCR
## Summary

GLM-OCR is a multimodal OCR model for complex document understanding, built on the GLM-V encoder-decoder architecture with Multi-Token Prediction (MTP) loss and reinforcement learning. Key features include:

- **Performance**: Achieves 94.62 on OmniDocBench V1.5, excelling in formula/table recognition and information extraction.
- **Efficiency**: 0.9B parameters, optimized for real-world scenarios (complex tables, seals, etc.), and supports deployment via vLLM, SGLang, and Ollama.
- **Ease of Use**: Open-sourced with SDK, one-line invocation, and integration toolchain.

**Deployment Options**:
1. **Zhipu MaaS API**: Cloud-based, no GPU required.
2. **Self-hosted**: vLLM/SGLang for full control.
3. **Ollama/MLX**: For specialized scenarios (e.g., Apple Silicon).
4. **SDK Server + Client**: GPU-less client setup.

**Architecture**: Modular (PageLoader, OCRClient, PPDocLayoutDetector, ResultFormatter) for customization. Supports CLI, Python API, and Flask service.

**License**: Apache 2.0 (code), MIT (model). Integrates PP-DocLayout-V3 (Apache 2.0). Citation available for research.
## Links

- [GLM-OCR Technical Report on arXiv](https://arxiv.org/abs/2603.10910) : The official technical report for GLM-OCR, providing detailed insights into its architecture, methodology, performance metrics, and research contributions.
- [GLM-OCR Model on Hugging Face](https://huggingface.co/zai-org/GLM-OCR) : The official Hugging Face repository for the GLM-OCR model, offering direct access to the model weights, usage examples, and integration guides.
- [GLM-OCR Model on ModelScope](https://modelscope.cn/models/ZhipuAI/GLM-OCR) : The ModelScope page for GLM-OCR, providing an alternative platform to access the model, along with deployment instructions and community support.
- [GLM-OCR API Documentation](https://docs.z.ai/guides/vlm/glm-ocr) : Official API documentation for GLM-OCR, detailing how to use the model via API calls, including authentication, endpoints, and example requests.
- [PP-DocLayoutV3 on Hugging Face](https://huggingface.co/PaddlePaddle/PP-DocLayoutV3) : The Hugging Face repository for PP-DocLayoutV3, a key component of GLM-OCR's pipeline for document layout analysis.

## Topics

![[topics/Model/GLM OCR]]

![[topics/Concept/Multi Token Prediction MTP]]

![[topics/Tool/SGLang]]

![[topics/Concept/Document Layout Analysis]]

![[topics/Library/PP DocLayout V3]]

![[topics/Tool/GLM OCR SDK]]

![[topics/Library/vLLM]]

![[topics/Tool/Ollama]]

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF]]