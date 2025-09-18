---
already_read: false
link: https://arxiv.org/pdf/2306.11644
read_priority: 3
relevance: 0
source: null
tags:
- Large_Language_Model
- Natural_Language_Processing
type: Content
upload_date: '2025-01-28'
---

https://arxiv.org/pdf/2306.11644
## Summary

The paper introduces phi-1, a new large language model for code with 1.3 billion parameters, trained on a high-quality dataset of 7 billion tokens. Despite its smaller size, phi-1 achieves state-of-the-art performance on coding benchmarks like HumanEval and MBPP, outperforming larger models. The key innovation is the use of "textbook-quality" data, which includes filtered code from web sources and synthetically generated textbooks and exercises using GPT-3.5. The model's architecture is based on a decoder-only Transformer with FlashAttention. Training was done on 8 A100 GPUs for about 4 days. Phi-1 demonstrates emergent properties and improved understanding and capability in using external libraries after finetuning on a small synthetic exercises dataset. The paper also discusses the importance of high-quality data in training language models and the potential environmental benefits of smaller models. Evaluation on unconventional problems and data pruning experiments further validate the model's performance. The paper concludes with a discussion on the limitations of phi-1 and the broader implications for natural language processing.
## Links


## Topics

![[topics/Concept/Scaling Laws)]]

![[topics/Model/Phi)]]

![[topics/Concept/Data Pruning)]]

![[topics/Concept/Data Decontamination)]]

![[topics/Concept/Model Emergent Properties)]]

![[topics/Concept/Synthetic Data Generation)]]

![[topics/Concept/Textbook Quality Data)]]