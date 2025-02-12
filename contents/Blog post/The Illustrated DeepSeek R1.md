---
already_read: false
link: https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1?utm_campaign=Data_Elixir&utm_source=Data_Elixir_522
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
- Deep_Learning
type: Content
upload_date: '2025-02-12'
---

https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1?utm_campaign=Data_Elixir&utm_source=Data_Elixir_522
## Summary

DeepSeek-R1 is a significant advancement in AI, particularly for the ML R&D community, as it is an open weights model designed for reasoning tasks. It builds on previous models and introduces a training method that emphasizes long chains of reasoning through a structured process.

Key points include:

1. **Training Process**: DeepSeek-R1 follows a three-step training process:
   - **Language Modeling**: Initial training on vast web data to create a base model.
   - **Supervised Fine-Tuning (SFT)**: Enhances the model's ability to follow instructions and answer questions.
   - **Preference Tuning**: Further refines the model to align with human preferences.

2. **Special Features**:
   - **Long Chains of Reasoning SFT Data**: Utilizes a large dataset of 600,000 reasoning examples, which are challenging to label.
   - **Interim Reasoning Model**: An earlier model that specializes in reasoning is used to generate SFT data, improving the overall model's performance.
   - **Reinforcement Learning (RL)**: Employs large-scale RL to create reasoning models, notably through the R1-Zero model, which excels at reasoning tasks without labeled data.

3. **Architecture**: DeepSeek-R1 consists of 61 Transformer decoder blocks, combining dense layers and mixture-of-experts layers to enhance its capabilities.

4. **Challenges**: While R1-Zero shows strong reasoning abilities, it faces issues like poor readability and language mixing, which R1 aims to address.

Overall, DeepSeek-R1 represents a step forward in developing reasoning-focused language models, leveraging innovative training techniques and architectures to improve performance across various tasks.
## Links

1. [Hands-On Large Language Models](https://github.com/handsOnLLM/Hands-On-Large-Language-Models) - A comprehensive resource for understanding and working with large language models, including code and examples.
2. [DeepSeek R1's recipe to replicate o1 and the future of reasoning LMs](https://www.interconnects.ai/p/deepseek-r1-recipe-for-o1) - An article discussing the methodology behind the DeepSeek-R1 model and its implications for reasoning in language models.
3. [Putting RL back in RLHF with RLOO](https://huggingface.co/blog/putting_rl_back_in_rlhf_with_rloo) - A blog post that explores the integration of reinforcement learning in the context of human feedback for language models.
4. [A Visual Guide to Mixture of Experts (MoE)](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-reasoning-llms?) - A visual guide that explains the concept of mixture of experts in language models, relevant to understanding the architecture of DeepSeek-R1.
5. [Open R1](https://github.com/huggingface/open-r1) - The Hugging Face project aimed at openly reproducing the DeepSeek-R1 model, providing access to code and resources for further exploration.
## Topics

![](topics/Model/DeepSeek%20R1)

![](topics/Model/R1%20Zero)

![](topics/Concept/Supervised%20Fine%20Tuning%20SFT)

![](topics/Concept/Reinforcement%20Learning)

![](topics/Concept/Mixture%20of%20Experts)