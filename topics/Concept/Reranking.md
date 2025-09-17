---
type: Concept
---

Reranking is a method used to improve the relevance of retrieved documents in information retrieval systems. It involves using a reranking model, often referred to as a cross-encoder, to assess the similarity between each query-document pair. This allows for the rearrangement of documents according to their relevance to the query. Reranking is typically applied after an initial search using similarity scores, enabling a broader selection of documents to be considered. For instance, a system might retrieve the 20 most similar documents, rerank them, and select only the top 5 to provide as context for a language model.