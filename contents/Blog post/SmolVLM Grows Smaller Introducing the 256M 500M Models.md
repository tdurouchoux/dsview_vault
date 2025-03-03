---
already_read: false
link: https://huggingface.co/blog/smolervlm
read_priority: 4
relevance: 0
source: null
tags:
- Large_Language_Model
- Computer_Vision
type: Content
upload_date: '2025-03-03'
---

https://huggingface.co/blog/smolervlm
## Summary

SmolVLM has introduced two new models: SmolVLM-256M and SmolVLM-500M, which are the smallest Vision Language Models (VLMs) available, designed for efficiency and strong multimodal performance. Key features include:

- **Model Sizes**: 256M and 500M parameters, significantly smaller than the previous 2B model while maintaining performance.
- **Vision Encoder**: A smaller SigLIP base patch-16/512 encoder is used, which processes images at a larger resolution for better understanding.
- **Training Optimization**: New tokenization techniques have improved real-world benchmarks, enhancing model stability and performance.
- **Use Cases**: Both models excel in tasks like image captioning, document Q&A, and basic visual reasoning.
- **Fine-tuning and Integration**: The models are compatible with existing frameworks like transformers and MLX, and they support ONNX for broader applications.

The release aims to cater to users with constrained devices and those needing cost-effective solutions for large data processing. The models are positioned to complement the existing SmolLM2 family, providing a comprehensive set of smaller LLM and VLM options.
## Links

1. [Fine-tuning SmolVLM using direct preference optimization (DPO) with TRL on a consumer GPU](https://huggingface.co/learn/cookbook/fine_tuning_vlm_dpo_smolvlm_instruct) - A guide on how to fine-tune the SmolVLM models using direct preference optimization techniques.
2. [ColSmolVLM GitHub Repository](https://github.com/DS4SD/docling) - The repository for ColSmolVLM, which focuses on multimodal retrieval and performance improvements.
3. [The Cauldron Dataset](https://huggingface.co/datasets/HuggingFaceM4/the_cauldron) - A dataset used in training the SmolVLM models, emphasizing document understanding.
4. [MathWriting Dataset](https://huggingface.co/datasets/HuggingFaceM4/mathwriting-google) - A dataset that contributes to the training of the SmolVLM models, particularly in understanding mathematical content.
5. [SmolVLM-500M-Instruct WebGPU Demo](https://huggingface.co/spaces/HuggingFaceTB/SmolVLM-500M-Instruct-WebGPU) - A demo showcasing the capabilities of the SmolVLM-500M model using WebGPU for inference.
## Topics

![](topics/Model/SmolVLM%20256M)

![](topics/Model/SmolVLM%20500M)

![](topics/Concept/Multimodal%20Retrieval)

![](topics/Tool/ColSmolVLM)

![](topics/Tool/ONNX)