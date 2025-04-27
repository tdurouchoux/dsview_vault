---
already_read: false
link: https://eugeneyan.com//writing/recsys-llm/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Large_Language_Model
- Data_Engineering
type: Content
upload_date: '2025-03-19'
---

https://eugeneyan.com//writing/recsys-llm/
## Summary

Recommendation systems and search are evolving with the integration of large language models (LLMs) and multimodal content. Key advancements include:

1. **LLM-augmented Architectures**: Hybrid models combine language capabilities with traditional behavioral modeling to address challenges like cold-start and long-tail recommendations. Techniques like Semantic IDs leverage content-derived features for more efficient user history representation.

2. **LLM-assisted Data Generation**: Organizations are using LLMs for tasks like generating webpage metadata and enhancing training datasets. For example, Bing improved its recommendation quality by using LLMs to create high-quality summaries, resulting in reduced clickbait and improved authority content in recommendations.

3. **Scaling Laws and Transfer Learning**: There is a focus on understanding how model size and training data affect performance. Research shows predictable benefits from larger models and data, with strategies like knowledge distillation and parameter-efficient fine-tuning techniques (e.g., LoRAs) enhancing efficiency.

4. **Unified Architectures**: A trend towards unified systems that combine search and recommendation tasks is emerging. These architectures, such as Spotify's generative retrieval model and LinkedIn’s 360Brew, demonstrate improved performance and reduced operational complexity by leveraging shared infrastructure.

Overall, these advancements illustrate how integrating LLMs can enhance recommendation systems and search functionalities, driving performance improvements while mitigating challenges in data scarcity and personalization.
## Links

- [CALRec: Contrastive Alignment of Generative LLMs for Sequential Recommendation](https://doi.org/10.48550/arXiv.2405.02429) : This paper discusses how to leverage generative language models for improving sequential recommendations through contrastive learning.
- [A Comprehensive Framework for Cross-Domain Click-Through Rate Prediction](https://doi.org/10.48550/arXiv.2408.16238) : This research focuses on enhancing click-through rate predictions across different domains using a transfer learning approach.
- [Scaling Laws of Large Sequential Recommendation Models](https://doi.org/10.48550/arXiv.2311.11351) : The paper investigates performance improvements in recommendation models as scale increases, exploring the relationship between model size and training data quantity.
- [360Brew: A Decoder-Only Foundation Model for Personalized Ranking and Recommendation](https://doi.org/10.48550/arXiv.2501.16450) : This study introduces a unified decoder-only model for handling various ranking and recommendation tasks, highlighting performance benefits over specialized models.
- [Self-Auxiliary Distillation for Sample Efficient Learning in Google-Scale Recommenders](https://doi.org/10.48550/arXiv.2408.14678) : This research presents a strategy for improving sample efficiency in large-scale recommendation systems through a self-auxiliary distillation framework.

## Topics

![](topics/Concept/Semantic%20Item%20Representation)

![](topics/Concept/Multimodal%20Learning)

![](topics/Tool/Residual%20Quantization%20Variational%20AutoEncoder%20RQ%20VAE)

![](topics/Model/Multi%20task%20Production%20Ranking%20Model)

![](topics/Concept/Transfer%20Learning)

![](topics/Concept/Knowledge%20Distillation%20in%20Recommendations)

![](topics/Platform/Unified%20Contextual%20Recommender%20Systems)

![](topics/Concept/A%20B%20Testing%20in%20Recommendation%20Systems)

![](topics/Dataset/Amazon%20Review%20Dataset%202018)

![](topics/Concept/User%20Sequence%20Modeling)