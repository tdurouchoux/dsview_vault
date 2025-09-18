---
already_read: false
link: https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
- Deep_Learning
type: Content
upload_date: '2025-02-12'
---

https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1
## Summary

DeepSeek-R1 is an open-weights language model designed for reasoning tasks, following a unique training recipe. It builds upon the base model from DeepSeek-V3 and involves three key steps:

1. **Long chains of reasoning SFT Data**: Utilizes 600,000 long chain-of-thought reasoning examples, which are expensive to label manually.
2. **Interim high-quality reasoning LLM**: Creates an unnamed sibling model specializing in reasoning, which is worse at non-reasoning tasks but generates data for the final model.
3. **Large-scale reinforcement learning (RL)**: Involves two phases:
   - **R1-Zero**: Uses RL to create an interim reasoning model without labeled SFT data, leveraging automatic verification for reasoning tasks.
   - **General RL training phase**: Enhances the model's reasoning and non-reasoning capabilities using helpfulness and safety reward models.

The architecture of DeepSeek-R1 consists of 61 Transformer decoder blocks, with the first three being dense and the rest being mixture-of-experts layers. The model excels at math and reasoning problems by generating thinking tokens to process problems thoroughly. The training process involves creating a base model, fine-tuning it for instructions, and further polishing it through preference tuning. The model's success highlights the potential of modern base models and the effectiveness of automatic verification for reasoning tasks.
## Links

- [DeepSeek-R1 Notion Page](https://tulip-phalange-a1e.notion.site/DeepSeek-R1-189c32470be2801c94b6e5648735447d) : A Notion page dedicated to DeepSeek-R1, likely containing detailed information, notes, or documentation about the model.
- [Hands-On Large Language Models Book](https://www.llm-book.com/) : The official website for the book 'Hands-On Large Language Models,' which provides foundational knowledge on how language models work.
- [Hugging Face Blog on RLHF](https://huggingface.co/blog/putting_rl_back_in_rlhf_with_rloo) : A blog post on Hugging Face discussing the reinforcement learning from human feedback (RLHF) and its implementation.
- [GitHub Repository for Hands-On Large Language Models](https://github.com/handsOnLLM/Hands-On-Large-Language-Models) : The GitHub repository for the book 'Hands-On Large Language Models,' containing code and additional resources.
- [Open R1 Hugging Face Project](https://github.com/huggingface/open-r1) : A Hugging Face project aimed at openly reproducing the DeepSeek-R1 model, providing resources and implementations.

## Topics

![[topics/Concept/Reinforcement Learning)]]

![[topics/Concept/Mixture of Experts MoE)]]

![[topics/Concept/Supervised Fine Tuning)]]

![[topics/Model/DeepSeek R1 Zero)]]

![[topics/Model/DeepSeek R1)]]