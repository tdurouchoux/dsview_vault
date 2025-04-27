---
already_read: false
link: https://huggingface.co/blog/smolervlm
read_priority: 4
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2025-03-03'
---

https://huggingface.co/blog/smolervlm
## Summary

Two new models, SmolVLM-256M and SmolVLM-500M, have been introduced to the SmolVLM family, marking significant advancements in lightweight Vision Language Models (VLMs) with 256M and 500M parameters, respectively. This release focuses on maintaining strong multimodal performance while reducing model size for more efficient processing and integration, especially on constrained devices.

Key technical advancements since SmolVLM 2B include:
- Selection of a smaller vision encoder (SigLIP base patch-16/512) over a larger one, yielding similar results but with reduced overhead.
- Increased image resolution processing capabilities, enhancing visual understanding.
- Optimized training methods, including improved tokenization strategies, to boost performance and model stability.
- A balanced data mixture emphasizing document understanding and image captioning.

The new models facilitate multimodal tasks such as captioning and document Q&A while providing fine-tuning options for specialized applications. Both SmolVLM models are readily compatible with transformers and support ONNX formats for further usability.
## Links

- [SmolVLM - 500M Instruct WebGPU Demo](https://huggingface.co/spaces/HuggingFaceTB/SmolVLM-500M-Instruct-WebGPU) : A demo showcasing the capabilities of the SmolVLM-500M model using WebGPU.
- [SmolVLM - 256M Instruct WebGPU Demo](https://huggingface.co/spaces/HuggingFaceTB/SmolVLM-256M-Instruct-WebGPU) : A demo showcasing the capabilities of the SmolVLM-256M model using WebGPU.
- [Fine-tuning SmolVLM using DPO](https://huggingface.co/learn/cookbook/fine_tuning_vlm_dpo_smolvlm_instruct) : A comprehensive guide to fine-tuning the SmolVLM models using Direct Preference Optimization.
- [The Cauldron Dataset](https://huggingface.co/datasets/HuggingFaceM4/the_cauldron) : Dataset used in the training of SmolVLM models that focuses on multimodal understanding.
- [Docmatix Dataset](https://huggingface.co/datasets/HuggingFaceM4/Docmatix) : A dataset that is part of the training mixture for the new SmolVLM models, emphasizing document understanding.

## Topics

![](topics/Model/SmolVLM)

![](topics/Library/Transformers)

![](topics/Concept/Tokenization)

![](topics/Tool/ONNX)

![](topics/Concept/Multimodal%20Learning)