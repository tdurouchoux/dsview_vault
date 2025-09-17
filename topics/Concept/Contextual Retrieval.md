---
type: Concept
---

Contextual Retrieval is an advanced method that improves the retrieval step in RAG by using Contextual Embeddings and Contextual BM25. This technique reduces the number of failed retrievals by 49% and, when combined with reranking, by 67%. It involves prepending chunk-specific explanatory context to each chunk before embedding and creating the BM25 index, thereby enhancing retrieval accuracy and performance in downstream tasks.