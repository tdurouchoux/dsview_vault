---
already_read: false
link: https://magazine.sebastianraschka.com/p/from-gpt-2-to-gpt-oss-analyzing-the
read_priority: 4
relevance: 0
source: Blef
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2025-11-12'
---

https://magazine.sebastianraschka.com/p/from-gpt-2-to-gpt-oss-analyzing-the
## Summary

OpenAI released gpt-oss-120b and gpt-oss-20b, their first open-weight models since GPT-2 in 2019. These models can run locally thanks to clever optimizations. The architecture has evolved since GPT-2, with notable changes including the removal of dropout, the use of RoPE for positional embeddings, Swish/SwiGLU activation functions, Mixture-of-Experts (MoE) for feed-forward modules, Grouped Query Attention (GQA) replacing Multi-Head Attention, sliding window attention, and RMSNorm replacing LayerNorm. The gpt-oss models are compared to Qwen3, a recent architecture, highlighting differences in width versus depth, the number of experts, and attention mechanisms. The models are licensed under Apache 2.0, allowing for commercial use. OpenAI also released GPT-5, with benchmarks showing that gpt-oss models perform comparably to proprietary models. The article concludes by discussing the potential of open-weight models and their future in the AI landscape.
## Links

- [OpenAI GPT-5 Introduction](https://openai.com/index/introducing-gpt-5/) : Official announcement page for GPT-5, detailing its features and advancements.
- [OpenAI GPT-OSS Model Card](https://openai.com/index/gpt-oss-model-card/) : Official model card for GPT-OSS, providing detailed specifications and performance metrics.
- [Hugging Face GPT-OSS 120B](https://huggingface.co/openai/gpt-oss-120b) : Hugging Face repository for the GPT-OSS 120B model, including model weights and usage instructions.
- [Hugging Face GPT-OSS 20B](https://huggingface.co/openai/gpt-oss-20b) : Hugging Face repository for the GPT-OSS 20B model, including model weights and usage instructions.
- [Qwen3 Model on Hugging Face](https://huggingface.co/Qwen/Qwen3-235B-A22B-Thinking-2507) : Hugging Face repository for the Qwen3 model, providing access to model weights and related resources.

## Topics

![[topics/Concept/Rotary Position Embedding RoPE]]

![[topics/Concept/Swish Activation Function]]

![[topics/Concept/SwiGLU Activation Function]]

![[topics/Concept/Mixture of Experts MoE]]

![[topics/Concept/Grouped Query Attention GQA]]

![[topics/Concept/Sliding Window Attention]]

![[topics/Concept/RMSNorm]]

![[topics/Concept/Attention Sinks]]

![[topics/Concept/MXFP4 Optimization]]