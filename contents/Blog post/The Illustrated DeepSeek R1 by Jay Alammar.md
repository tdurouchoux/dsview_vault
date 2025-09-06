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

DeepSeek-R1 is a significant open-weights language model designed for reasoning tasks. It follows a three-step training process: language modeling, supervised fine-tuning (SFT), and preference tuning. The model's unique aspects include:

1. **Long chains of reasoning SFT Data**: DeepSeek-R1 uses 600,000 long chain-of-thought reasoning examples, which are expensive and hard to obtain.

2. **Interim high-quality reasoning LLM**: An unnamed sibling model specializing in reasoning generates the SFT reasoning examples. This model is created using large-scale reinforcement learning (RL) and excels at solving reasoning problems but is worse at non-reasoning tasks.

3. **Creating reasoning models with large-scale RL**: DeepSeek-R1-Zero, an earlier model, is trained directly from a pre-trained base model through RL without an SFT step. It excels at reasoning tasks and is competitive with OpenAI's O1 model. The RL process uses automatic verification to improve the model's reasoning capabilities.

DeepSeek-R1's architecture consists of 61 Transformer decoder blocks, with the first three being dense and the rest being mixture-of-experts layers. The model's training process involves creating an interim reasoning model to generate SFT data points and then training the R1 model to improve on both reasoning and non-reasoning problems.

The key takeaway is that DeepSeek-R1 demonstrates a novel approach to creating reasoning models using large-scale RL and automatic verification, which reduces the dependency on labeled data and improves the model's reasoning capabilities.
## Links

- [Hands-On Large Language Models Book on Amazon](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961) : Official website of the book. You can order the book on Amazon. All code is uploaded to GitHub.
- [GitHub Repository for Hands-On Large Language Models](https://github.com/handsOnLLM/Hands-On-Large-Language-Models) : All code related to the book is uploaded to this GitHub repository.
- [DeepSeek R1's recipe to replicate o1 and the future of reasoning LMs](https://www.interconnects.ai/p/deepseek-r1-recipe-for-o1) : A blog post discussing the recipe for DeepSeek R1 and its implications for the future of reasoning language models.
- [DeepSeek R1 Technical Report](https://arxiv.org/pdf/2401.06066) : Technical report detailing the architecture and training process of DeepSeek R1.
- [Open R1 HuggingFace Project](https://github.com/huggingface/open-r1) : HuggingFace project to openly reproduce DeepSeek-R1.

## Topics

![](topics/Model/DeepSeek%20R1)

![](topics/Model/DeepSeek%20R1%20Zero)

![](topics/Concept/Reinforcement%20Learning%20from%20Human%20Feedback%20RLHF)

![](topics/Concept/Supervised%20Fine%20Tuning%20SFT)

![](topics/Concept/Mixture%20of%20Experts%20MoE)