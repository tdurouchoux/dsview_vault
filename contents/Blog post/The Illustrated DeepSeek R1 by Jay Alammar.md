---
already_read: false
link: https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2025-02-12'
---

https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1
## Summary

DeepSeek-R1 is a recent advancement in AI, specifically targeting reasoning capabilities in language models. It features an open weights model and incorporates a new training method to reproduce reasoning models like OpenAI O1. 

Key components of DeepSeek-R1's training include:
1. **Long Chains of Reasoning SFT Data**: Utilizes 600,000 examples of complex reasoning tasks generated with minimal human intervention, providing high-quality training data.
2. **Interim Reasoning Model**: This model, developed from another precursor, focuses on reasoning tasks and is used to create data for training more general models.
3. **Reinforcement Learning (RL)**: The model employs large-scale RL (R1-Zero) capable of reasoning without labeled training sets. RL further refines DeepSeek-R1, enabling it to tackle both reasoning and non-reasoning tasks.
4. **Architecture**: Consists of stackable Transformer decoder blocks, utilizing 61 layers, a mix of dense and mixture-of-experts configurations.

The training method balances the development of strong reasoning capabilities with usability for broader tasks. Key takeaway: The integration of RL and innovative data generation techniques allows DeepSeek-R1 to advance the capabilities of reasoning in language models effectively.
## Links

- [Hands-On Large Language Models](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961) : A comprehensive book that provides foundational knowledge on large language models, important for understanding DeepSeek-R1.
- [Open R1 project on HuggingFace](https://github.com/huggingface/open-r1) : An open-source project that aims to reproduce the DeepSeek-R1 model, providing resources for further experimentation.
- [A Visual Guide to Mixture of Experts (MoE)](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-reasoning-llms?) : An insightful visual guide explaining the mixture of experts architecture, which is relevant to understanding the architecture of DeepSeek-R1.
- [Putting RL back in RLHF](https://huggingface.co/blog/putting_rl_back_in_rlhf_with_rloo) : A blog post discussing the integration of Reinforcement Learning in the context of Human Feedback (RLHF), pertinent to the training approaches of reasoning LLMs.
- [Introduction to Transformers by Jay Alammar](https://jalammar.github.io/illustrated-transformer/) : A visual exploration of transformer models providing background context necessary for understanding how models like DeepSeek-R1 operate.

## Topics

![](topics/Concept/Reasoning%20Models)

![](topics/Model/DeepSeek%20R1)

![](topics/Concept/Reinforcement%20Learning)

![](topics/Concept/Supervised%20Fine%20Tuning%20SFT)

![](topics/Dataset/Long%20Chain%20of%20Thought%20Reasoning%20Data)

![](topics/Concept/Mixture%20of%20Experts%20MoE)