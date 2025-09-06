---
already_read: true
link: https://arxiv.org/pdf/2412.15605
read_priority: 3
relevance: 0
source: Blef
tags:
- Large_Language_Model
type: Content
upload_date: '2025-01-15'
---

https://arxiv.org/pdf/2412.15605
## Summary

The paper introduces Cache-Augmented Generation (CAG), a new approach for knowledge tasks that leverages the extended context windows of large language models (LLMs) to eliminate the need for real-time retrieval, which is a key challenge in traditional Retrieval-Augmented Generation (RAG) systems. CAG preloads all relevant documents into the LLM's context and precomputes the key-value (KV) cache, allowing the model to generate responses without additional retrieval steps during inference. This method eliminates retrieval latency, minimizes retrieval errors, and simplifies system architecture. The paper presents a comparative analysis showing that CAG can outperform or complement traditional RAG pipelines in scenarios with manageable knowledge bases. The methodology involves three phases: external knowledge preloading, inference using the precomputed KV cache, and cache reset for maintaining system performance. Experiments on the SQuAD and HotPotQA datasets demonstrate that CAG achieves higher BERTScores and reduces response times compared to RAG systems, particularly as the size of the knowledge base increases. The paper concludes by discussing the potential for hybrid approaches that combine preloading with selective retrieval and acknowledges limitations related to the size of the knowledge base that can be preloaded.
## Links


## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Cache%20Augmented%20Generation%20CAG)

![](topics/Concept/Key%20Value%20KV%20Cache)

![](topics/Concept/Long%20Context%20LLMs)

![](topics/Dataset/Stanford%20Question%20Answering%20Dataset%20SQuAD)

![](topics/Dataset/HotPotQA)