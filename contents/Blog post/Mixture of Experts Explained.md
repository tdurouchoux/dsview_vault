---
already_read: true
link: https://huggingface.co/blog/moe
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-11-18'
---

https://huggingface.co/blog/moe
## Summary

Mixture of Experts (MoEs) are models that enable efficient pretraining and faster inference compared to dense models. They consist of sparse MoE layers with multiple experts and a gate network that routes tokens to these experts. MoEs have a history dating back to 1991, with significant advancements in the 2010s, particularly in the context of NLP. Sparsity in MoEs allows for conditional computation, where only parts of the network are active for specific inputs, leading to efficient training and inference.

Key challenges include training instabilities and high VRAM requirements. Techniques like load balancing, expert capacity, and router Z-loss help stabilize training. MoEs can be fine-tuned, but they require different hyperparameter setups and may benefit from instruction tuning. The choice between MoEs and dense models depends on the use case, with MoEs being more suitable for high-throughput scenarios and dense models for low-throughput ones.

Efficient training and serving techniques, such as parallelism, capacity factor adjustment, and expert aggregation, are crucial for practical implementation. Open-source projects and resources are available for further exploration and experimentation with MoEs.
## Links

- [Mixture of Experts Explained](https://github.com/huggingface/blog/blob/main/moe.md) : The markdown file for the blog post explaining Mixture of Experts (MoE) on Hugging Face.
- [Switch Transformers Paper](https://arxiv.org/abs/2101.03961) : The paper introducing Switch Transformers, a type of Mixture of Experts model.
- [Mixtral 8x7B Model](https://huggingface.co/mistralai/Mixtral-8x7B-v0.1) : The Mixtral 8x7B model, a Mixture of Experts model released by Mistral AI.
- [Mixtral of Experts Blog Post](https://mistral.ai/news/mixtral-of-experts/) : A blog post announcing the Mixtral 8x7B model and discussing its performance and capabilities.

## Topics

![[topics/Concept/Mixture of Experts MoE]]

![[topics/Concept/Sparsity]]

![[topics/Concept/Expert Capacity]]

![[topics/Concept/Router Z loss]]

![[topics/Concept/Parallelism]]

![[topics/Concept/Load Balancing]]

![[topics/Concept/Switch Transformers]]

![[topics/Concept/Serving Techniques]]

![[topics/Concept/Fine tuning MoEs]]