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

The article introduces two new models, SmolVLM-256M and SmolVLM-500M, which are smaller versions of the SmolVLM family. The 256M model is the smallest Vision Language Model (VLM) in the world, while the 500M model offers a balance between performance and memory usage. Both models are designed to be efficient and lightweight, making them suitable for constrained devices, consumer laptops, or browser-based inference. They also offer significant cost savings for processing large amounts of data.

Key improvements include a smaller vision encoder (SigLIP base patch-16/512) that processes images at a larger resolution, a new tokenization trick that boosts real-world benchmarks, and an updated data mixture that emphasizes document understanding and image captioning. The models are compatible with transformers, MLX, and ONNX, and there are demos available for transformers and WebGPU.

The article also mentions the ColSmolVLM models, which are fine-tuned versions of SmolVLM that deliver state-of-the-art multimodal retrieval speeds. Additionally, the SmolVLM models are being used in the Docling project, with impressive early results.

The article concludes with information on how to use the new SmolVLM models, including code examples for transformers and MLX, and links to fine-tuning and multimodal RAG with ColSmolVLM. The authors express excitement about the potential uses of the new models and encourage readers to explore them further.
## Links

- [SmolVLM-256M-Instruct-WebGPU](https://huggingface.co/spaces/HuggingFaceTB/SmolVLM-256M-Instruct-WebGPU) : WebGPU demo for the SmolVLM-256M-Instruct model.
- [SmolVLM-500M-Instruct-WebGPU](https://huggingface.co/spaces/HuggingFaceTB/SmolVLM-500M-Instruct-WebGPU) : WebGPU demo for the SmolVLM-500M-Instruct model.
- [Fine-tuning SmolVLM using direct preference optimization (DPO) with TRL on a consumer GPU](https://huggingface.co/learn/cookbook/fine_tuning_vlm_dpo_smolvlm_instruct) : Guide on fine-tuning SmolVLM using direct preference optimization (DPO) with TRL on a consumer GPU.

## Topics

![](topics/Model/SmolVLM%20256M)

![](topics/Model/SmolVLM%20500M)

![](topics/Concept/Multimodal%20Retrieval)

![](topics/Concept/Tokenization%20Optimization)