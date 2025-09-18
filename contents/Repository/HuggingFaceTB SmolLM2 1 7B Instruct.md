---
already_read: false
link: https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct
read_priority: 4
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2025-01-08'
---

https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct
## Summary

SmolLM2 is a family of compact language models available in three sizes (135M, 360M, and 1.7B parameters), designed for on-device use. The 1.7B variant shows improvements in instruction following, knowledge, reasoning, and mathematics over its predecessor. It was trained on 11 trillion tokens using diverse datasets and fine-tuned with supervised fine-tuning (SFT) and Direct Preference Optimization (DPO). The instruct model supports tasks like text rewriting, summarization, and function calling.

Key features include:
- Evaluation results show significant improvements over previous models and competitors in various benchmarks.
- The model can be used with Transformers, TRL CLI, and Transformers.js.
- Examples provided for text rewriting, summarization, and function calling.
- Limitations include potential inaccuracies, biases, and the need for critical evaluation of generated content.
- Trained using a Transformer decoder architecture with 11 trillion tokens and bfloat16 precision on 256 H100 GPUs.
- Licensed under Apache 2.0.

The model is available for download and use, with various inference providers and spaces utilizing it.
## Links

- [SmolLM2-1.7B-Instruct GitHub Repository](https://github.com/huggingface/smollm) : The GitHub repository for SmolLM2-1.7B-Instruct, containing pre-training, post-training, evaluation, and local inference code.
- [SmolLM2 Research Paper](https://arxiv.org/abs/2502.02737v1) : The research paper detailing the development and performance of the SmolLM2 language models.

## Topics

![[topics/Concept/UltraFeedback]]

![[topics/Model/SmolLM2]]

![[topics/Concept/Direct Preference Optimization DPO]]

![[topics/Concept/Text Generation]]

![[topics/Concept/Supervised Fine Tuning]]