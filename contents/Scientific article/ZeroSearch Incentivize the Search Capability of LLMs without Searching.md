---
already_read: false
link: https://alibaba-nlp.github.io/ZeroSearch/
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
- Supervised_Learning
type: Content
upload_date: '2025-05-09'
---

https://alibaba-nlp.github.io/ZeroSearch/
## Summary

ZeroSearch is a reinforcement learning (RL) framework designed to enhance the search capabilities of large language models (LLMs) without the need for real search engine interactions during training. The key challenges addressed are the uncontrolled document quality and high API costs associated with real search engines.

**Main Technical Points:**

1. **Supervised Fine-Tuning (SFT):** ZeroSearch begins with lightweight SFT to transform the LLM into a retrieval module capable of generating both useful and noisy documents in response to a query.

2. **Curriculum Rollout Mechanism:** During RL training, a curriculum-based rollout strategy is employed to progressively degrade the quality of generated documents, thereby eliciting the model’s reasoning ability through increasingly challenging retrieval scenarios.

3. **Optimization Objective:** The optimization objective is formulated to maximize the expected reward while minimizing the KL divergence between the policy model and a reference model.

4. **Reward Design:** The reward signal is based on the F1 score, focusing solely on answer accuracy.

**Key Takeaways:**

- ZeroSearch outperforms baseline methods, including those using real search engines, across various datasets and model types.
- It demonstrates strong generalizability and scalability, with performance improving as model size increases.
- Fine-tuned simulation engines significantly outperform prompt-based ones, and larger simulation LLMs show stronger simulation capabilities.
- The framework effectively incentivizes the model’s search capabilities, as evidenced by multi-turn search behaviors in case studies.

Overall, ZeroSearch provides a cost-effective and scalable alternative to real search engines for enhancing the search capabilities of LLMs.
## Links

- [ZeroSearch Dataset](https://huggingface.co/datasets/sunhaonlp/ZeroSearch_dataset) : This link points to the dataset used in the ZeroSearch project, which is hosted on Hugging Face Datasets. The dataset likely contains the data used for training and evaluating the ZeroSearch model.
- [ZeroSearch GitHub Repository](https://github.com/Alibaba-nlp/ZeroSearch) : This link points to the GitHub repository of the ZeroSearch project. It likely contains the source code, models, and additional resources related to the ZeroSearch framework.
- [ZeroSearch Paper](https://arxiv.org/pdf/2505.04588) : This link points to the research paper detailing the ZeroSearch framework. It provides an in-depth explanation of the methodology, experiments, and results of the ZeroSearch project.

## Topics

![[topics/Concept/Reinforcement Learning]]

![[topics/Concept/Supervised Fine Tuning]]

![[topics/Model/ZeroSearch]]

![[topics/Concept/Curriculum Learning]]