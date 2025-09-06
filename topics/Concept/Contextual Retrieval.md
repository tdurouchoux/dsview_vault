---
type: Concept
---

Contextual Retrieval is a method that improves the retrieval step in RAG by using two sub-techniques: Contextual Embeddings and Contextual BM25. It prepends chunk-specific explanatory context to each chunk before embedding and creating the BM25 index, which helps to reduce the number of failed retrievals and improve retrieval accuracy.