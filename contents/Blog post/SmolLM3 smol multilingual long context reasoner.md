---
already_read: true
link: https://huggingface.co/blog/smollm3
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2025-07-20'
---

https://huggingface.co/blog/smollm3
## Summary

SmolLM3 is a new small, multilingual, long-context reasoning model developed by Hugging Face, featuring a 3 billion parameter architecture designed for efficiency and competitive performance. Highlights include:

- **Model Performance**: The model performs exceptionally at the 3B scale, surpassing competitors like Llama-3.2-3B and Qwen2.5-3B and competing with larger models (4B) in various benchmarks. It supports six languages and has long-context capabilities of up to 128k tokens.

- **Architecture & Training**: Built on a transformer decoder architecture with innovations like Grouped Query Attention (GQA) for reduced KV cache size, and NoPE for enhanced long-context capabilities. The training utilized a three-stage process on 11.2 trillion tokens, mixing web, math, and code data with specific proportions.

- **Mid-training for Long Context & Reasoning**: Following pretraining, the model underwent mid-training to extend context length (up to 128k) and improve reasoning capabilities through additional fine-tuning.

- **Dual Instruction/Reasoning Model**: SmolLM3 incorporates a dual-mode system allowing users to switch between reasoning and non-reasoning modes via designated system prompts. This includes supervised fine-tuning and alignment using Anchored Preference Optimization for balanced performance across tasks.

- **Tool Support**: The model supports tool calling, allowing integration of external functionalities like weather queries.

- **Evaluation Results**: SmolLM3 shows competitive edge across multiple evaluation benchmarks in knowledge, reasoning, math, and coding tasks. Its performance in multilingual contexts is robust, demonstrating its utility across languages.

Overall, SmolLM3's release includes the complete training recipe and encourages further community experimentation and development.
## Links

- [SmolLM GitHub repo with pretraining configs and evaluation code](https://github.com/huggingface/smollm) : This repository contains the code and configuration files for pretraining and evaluating the SmolLM models.
- [Llama-Nemotron-Post-Training-Dataset](https://huggingface.co/datasets/nvidia/Llama-Nemotron-Post-Training-Dataset) : This dataset is related to the Llama model and may be useful for understanding post-training enhancements based on reasoning.
- [FineWeb-Edu dataset](https://huggingface.co/datasets/HuggingFaceFW/fineweb-edu) : An open dataset used for training models like SmolLM3, primarily focused on educational content.
- [MergeKit library](https://github.com/arcee-ai/mergekit) : A library designed to assist in model merging, facilitating improved performance of language models.
- [Nanotron GitHub repository](https://github.com/huggingface/nanotron) : Repository for the Nanotron framework, which includes tools for distributed training and efficient scaling.

## Topics

![](topics/Model/SmolLM3)

![](topics/Concept/Grouped%20Query%20Attention%20GQA)

![](topics/Concept/Anchored%20Preference%20Optimization%20APO)

![](topics/Concept/Synthetic%20Data%20Generation)

![](topics/Platform/Hugging%20Face)

![](topics/Concept/Dual%20Instruction%20Reasoning%20Mode)