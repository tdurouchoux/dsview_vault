---
already_read: false
link: https://ai.meta.com/blog/llama-4-multimodal-intelligence/
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2025-04-09'
---

https://ai.meta.com/blog/llama-4-multimodal-intelligence/
## Summary

Meta AI Research introduces the Llama 4 herd, marking a new era in multimodal AI innovation. The Llama 4 models are the first open-weight, natively multimodal models with unprecedented context length support and a mixture-of-experts (MoE) architecture.

Key models include:
- **Llama 4 Scout**: A 17 billion active parameter model with 16 experts, fitting on a single NVIDIA H100 GPU. It offers a 10M context window and outperforms competitors like Gemma 3 and Mistral 3.1.
- **Llama 4 Maverick**: A 17 billion active parameter model with 128 experts, beating GPT-4o and Gemini 2.0 Flash across various benchmarks, with a best-in-class performance-to-cost ratio.
- **Llama 4 Behemoth**: A 288 billion active parameter model with 16 experts, currently in training, serving as a teacher for the other models and outperforming GPT-4.5 and Claude Sonnet 3.7 on STEM benchmarks.

The models are designed with native multimodality, incorporating early fusion to integrate text and vision tokens. They use a MoE architecture for efficiency, with Llama 4 Maverick having 17B active parameters and 400B total parameters. The models were pre-trained on over 30 trillion tokens, including diverse text, image, and video datasets.

Post-training involved a revamped pipeline with lightweight supervised fine-tuning (SFT), online reinforcement learning (RL), and lightweight direct preference optimization (DPO). The models were trained on a wide variety of image and video frame stills for broad visual understanding.

Safeguards and protections include pre- and post-training mitigations, system-level approaches like Llama Guard and Prompt Guard, and evaluations through red-teaming and GOAT (Generative Offensive Agent Testing). The models aim to address bias, with Llama 4 performing better than previous versions in reducing bias and refusing responses less often on debated topics.

The Llama 4 models are available for download on llama.com and Hugging Face, with integrations in WhatsApp, Messenger, Instagram Direct, and the Meta.AI website. Meta AI Research continues to innovate and collaborate with partners across the AI community.
## Links

- [Llama 4 Models Download](https://www.llama.com/) : Download the Llama 4 Scout and Llama 4 Maverick models on llama.com.
- [LlamaCon Signup](https://www.llama.com/events/llamacon/signup/) : Sign up for LlamaCon to hear more about the future of Llama models and their applications.

## Topics

![[topics/Concept/Early Fusion]]

![[topics/Concept/Mixture of Experts MoE]]

![[topics/Concept/MetaP]]

![[topics/Model/Llama 4 Behemoth]]

![[topics/Concept/iRoPE Architecture]]

![[topics/Model/Llama 4 Maverick]]

![[topics/Model/Llama 4 Scout]]