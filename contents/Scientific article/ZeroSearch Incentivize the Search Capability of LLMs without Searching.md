---
already_read: false
link: https://alibaba-nlp.github.io/ZeroSearch/
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2025-05-09'
---

https://alibaba-nlp.github.io/ZeroSearch/
## Summary

The paper introduces ZeroSearch, a reinforcement learning (RL) framework designed to improve the search capabilities of large language models (LLMs) without requiring interaction with real search engines. The key challenges addressed by ZeroSearch include the unpredictability of document quality from search engines and high API costs associated with RL training.

Key points include:
- **Supervised Fine-Tuning (SFT)**: LLMs are initially fine-tuned using supervised learning to simulate search engine behavior. Positive and negative examples are used to enhance the LLM's retrieval abilities.
- **Curriculum-Based Rollout**: The training process involves a strategy that gradually increases the difficulty of retrieval scenarios, effectively building the model's reasoning skills.
- **Reward Mechanism**: A reward function based on the F1 score is used to measure the accuracy of answers, without needing additional formatting supervision.

Experimental results demonstrate that:
- ZeroSearch outperforms traditional models including those using real search engines across various datasets, both in-domain and out-of-domain.
- The approach shows scalability and generalizability across different model types and sizes, indicating its effectiveness across a range of scenarios.
- Larger simulation models yield better performance, with the best results observed in fine-tuned 7B and 14B models, which matched or exceeded the performance of real search engines.

In conclusion, ZeroSearch provides a cost-effective and efficient alternative for enhancing LLM search capabilities, showcasing promising results across various configurations and datasets.
## Links

- [ZeroSearch GitHub Repository](https://github.com/Alibaba-nlp/ZeroSearch) : Official repository for the ZeroSearch project providing code and implementation details.
- [ZeroSearch Dataset on Hugging Face](https://huggingface.co/datasets/sunhaonlp/ZeroSearch_dataset) : Access the ZeroSearch dataset which can be used for training and evaluation purposes.
- [ZeroSearch Paper on arXiv](https://arxiv.org/pdf/2505.04588) : The research paper outlining the ZeroSearch framework, its methodology, results, and conclusions.
- [Hugging Face Collection for ZeroSearch](https://huggingface.co/collections/sunhaonlp/zerosearch-681b4ce012b9b6899832f4d0) : A collection of models and datasets related to ZeroSearch hosted on Hugging Face.

## Topics

![](topics/Concept/Reinforcement%20Learning)

![](topics/Concept/Curriculum%20Learning)

![](topics/Tool/ZeroSearch)

![](topics/Concept/Supervised%20Fine%20tuning)

![](topics/Concept/Search%20Simulation)

![](topics/Concept/Reward%20Signal%20Design)