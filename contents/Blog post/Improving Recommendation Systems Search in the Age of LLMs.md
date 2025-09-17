---
already_read: false
link: https://eugeneyan.com//writing/recsys-llm/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2025-03-19'
---

https://eugeneyan.com//writing/recsys-llm/
## Summary

The content discusses advancements in recommendation systems and search, particularly in the context of large language models (LLMs). Key points include the integration of LLMs and multimodal content to enhance recommendation models, addressing challenges like cold-start and long-tail item recommendations. Several architectures and techniques are highlighted, such as Semantic IDs (YouTube), M3CSR (Kuaishou), FLIP (Huawei), beeFormer, CALRec (Google), and EmbSum (Meta), each demonstrating improvements in recommendation quality and performance. The use of LLMs for data generation and analysis is also explored, with examples from Bing, Indeed, Yelp, Spotify, and Amazon, showcasing enhancements in data quality and user experience. Additionally, the content covers scaling laws, transfer learning, distillation, and LoRAs, illustrating how these techniques improve model performance and efficiency. Finally, the shift towards unified architectures for search and recommendations is discussed, with examples from Spotify, LinkedIn, Netflix, Etsy, Best Buy, YouTube, and Zalando, demonstrating the benefits of integrated systems. Overall, the content emphasizes the potential of LLMs to enhance recommendation systems and search, backed by industry results.
## Links

- [360Brew: A Decoder-Only Foundation Model for Personalized Ranking and Recommendation](https://arxiv.org/abs/2501.16450) : This paper introduces 360Brew, a decoder-only foundation model designed for personalized ranking and recommendation tasks. It consolidates multiple ID-based ranking models into a single large model with a natural language interface, replacing traditional feature engineering with prompt engineering. The model is fine-tuned on extensive interaction data and supports over 30 different ranking tasks across LinkedIn’s platforms.
- [Unified Embedding Based Personalized Retrieval in Etsy Search](https://arxiv.org/abs/2306.04833) : This paper discusses how Etsy unified transformer-based, term-based, and graph-based embeddings within a two-tower model architecture to improve search and recommendation systems. The goal was to address gaps such as lexical matching and poor performance of neural embeddings due to limited user context. The model combines various embedding types and uses negative sampling techniques to enhance performance.
- [Scaling Law of Large Sequential Recommendation Models](https://arxiv.org/abs/2311.11351) : This paper investigates how the performance of ID-based sequential recommender models improves as their model size and data scale increase. The authors uncover a predictable power-law relationship where performance consistently improves with the expansion of both model size and dataset size. The study also explores the impact of model architecture and training paradigms on performance.

## Topics

![](topics/Concept/Semantic%20IDs)

![](topics/Concept/Multimodal%20Content%20Embeddings)

![](topics/Concept/FLIP%20Fine%20Grained%20Alignment%20between%20ID%20Based%20Models%20and%20Pretrained%20Language%20Models)

![](topics/Concept/beeFormer)

![](topics/Concept/CALRec%20Contrastive%20Alignment%20of%20Generative%20LLMs%20for%20Sequential%20Recommendation)

![](topics/Concept/EmbSum%20Embedding%20Summarization)

![](topics/Concept/Scaling%20Laws%20in%20Recommendation%20Systems)

![](topics/Concept/PrepRec%20Pretrained%20Recommendation)

![](topics/Concept/E%20CDCTR%20Efficient%20Cross%20Domain%20Click%20Through%20Rate%20Prediction)

![](topics/Concept/Knowledge%20Distillation)