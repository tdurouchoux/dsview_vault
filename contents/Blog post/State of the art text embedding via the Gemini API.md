---
already_read: false
link: https://developers.googleblog.com/en/gemini-embedding-text-model-now-available-gemini-api/
read_priority: 2
relevance: 0
source: Data Points
tags:
- Natural_Language_Processing
- Large_Language_Model
type: Content
upload_date: '2025-03-11'
---

https://developers.googleblog.com/en/gemini-embedding-text-model-now-available-gemini-api/
## Summary

Google has introduced an experimental Gemini Embedding text model (gemini-embedding-exp-03-07) via the Gemini API. This model, trained on the Gemini model, offers improved language understanding and context, making it suitable for various applications. Key features include:

- **Performance**: Achieves the top rank on the Massive Text Embedding Benchmark (MTEB) Multilingual leaderboard with a mean score of 68.32.
- **Generalization**: Works effectively out-of-the-box across diverse domains without extensive fine-tuning.
- **Applications**: Useful for tasks like retrieval augmented generation (RAG), recommendation systems, text classification, clustering, and text similarity.
- **Improvements**:
  - Input token limit of 8K tokens.
  - Output dimensions of 3K dimensions.
  - Matryoshka Representation Learning (MRL) for scalable storage.
  - Expanded language support to over 100 languages.
  - Unified model surpassing previous task-specific models.

The model is currently in an experimental phase with limited capacity, and feedback is welcomed. Developers can access it through the Gemini API, and it is compatible with the existing embed_content endpoint. The model will undergo changes before a stable, generally available release.
## Links

- [Gemini API Embeddings Documentation](https://ai.google.dev/gemini-api/docs/embeddings) : Official documentation for Gemini API embeddings, providing detailed information on how to use the embedding models.
- [Gemini API Models Documentation](https://ai.google.dev/gemini-api/docs/models/gemini#text-embedding) : Official documentation for Gemini API models, including details on the text embedding model.

## Topics

![](topics/Model/Gemini%20Embedding%20Model)

![](topics/Concept/Matryoshka%20Representation%20Learning)

![](topics/Tool/Massive%20Text%20Embedding%20Benchmark%20MTEB)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)