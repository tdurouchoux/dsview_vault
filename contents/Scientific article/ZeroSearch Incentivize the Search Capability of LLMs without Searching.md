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

ZeroSearch is a reinforcement learning (RL) framework designed to enhance the search capabilities of large language models (LLMs) without the need for real search engine interactions during training. The key aspects of ZeroSearch include:

1. **Supervised Fine-Tuning (SFT)**: Transforms the LLM into a retrieval module capable of generating both useful and noisy documents in response to a query.
2. **Curriculum Rollout Mechanism**: Progressively degrades the quality of generated documents to elicit the model’s reasoning ability by exposing it to increasingly challenging retrieval scenarios.
3. **Reward Design**: Uses an F1 score-based reward focusing on answer accuracy.
4. **Experiments**: Demonstrates that ZeroSearch outperforms baseline methods, including those using real search engines, and shows strong generalizability across different model families, sizes, and types.
5. **Simulation LLMs**: Fine-tuned LLMs (especially 7B and 14B) perform comparably or better than real search engines, highlighting the feasibility of using LLMs as substitutes for real search engines in RL setups.

ZeroSearch effectively incentivizes the search capabilities of LLMs while incurring zero API costs and maintaining robust performance across various datasets and model configurations.
## Links

- [ZeroSearch Paper](https://arxiv.org/pdf/2505.04588) : This link points to the research paper detailing the ZeroSearch framework, which incentivizes the search capabilities of large language models (LLMs) without the need for real search engines during training.
- [ZeroSearch Dataset](https://huggingface.co/datasets/sunhaonlp/ZeroSearch_dataset) : This link provides access to the dataset used in the ZeroSearch project, which includes interaction trajectories and query-document pairs for training and evaluating the model.
- [ZeroSearch Code Repository](https://github.com/Alibaba-nlp/ZeroSearch) : This link directs to the GitHub repository containing the source code for the ZeroSearch project, allowing users to explore and implement the framework.

## Topics

![](topics/Concept/Curriculum%20Learning)

![](topics/Model/ZeroSearch)

![](topics/Concept/Reinforcement%20Learning)

![](topics/Concept/Supervised%20Fine%20Tuning)