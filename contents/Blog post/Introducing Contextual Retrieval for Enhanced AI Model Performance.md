---
already_read: true
link: https://www.anthropic.com/news/contextual-retrieval
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-09-30'
---

https://www.anthropic.com/news/contextual-retrieval
## Summary

Anthropic introduces Contextual Retrieval, a method to improve Retrieval-Augmented Generation (RAG) by enhancing the retrieval step. Traditional RAG systems often fail to retrieve relevant information due to context loss during encoding. Contextual Retrieval addresses this by using two sub-techniques: Contextual Embeddings and Contextual BM25. These methods reduce failed retrievals by 49% and, when combined with reranking, by 67%.

Key points:
- Contextual Retrieval prepends chunk-specific explanatory context to each chunk before embedding and creating the BM25 index.
- For smaller knowledge bases (under 200,000 tokens), including the entire knowledge base in the prompt can be a simple and effective solution.
- Traditional RAG systems break down knowledge bases into chunks, convert them into vector embeddings, and store them in a vector database for semantic similarity searches.
- BM25 is a ranking function that uses lexical matching to find precise word or phrase matches, complementing semantic embeddings.
- Contextual Retrieval improves retrieval accuracy by providing more context to each chunk, making it easier to retrieve relevant information.
- The implementation involves using Claude to generate concise, chunk-specific context for each chunk, which is then prepended to the chunk before embedding and creating the BM25 index.
- Performance improvements are significant, with Contextual Embeddings reducing the top-20-chunk retrieval failure rate by 35%, and combining Contextual Embeddings and Contextual BM25 reducing it by 49%.
- Further performance improvements can be achieved by combining Contextual Retrieval with reranking, reducing the top-20-chunk retrieval failure rate by 67%.
- Developers can use a cookbook to implement Contextual Retrieval and experiment with these approaches to unlock new levels of performance.
## Links

- [Voyage Reranker Documentation](https://docs.voyageai.com/docs/reranker) : Documentation on Voyage reranker, which is mentioned as a tool for boosting performance.
- [Contextual Embeddings Cookbook](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/contextual-embeddings) : A cookbook guide on implementing contextual embeddings for improved retrieval accuracy.
- [Evaluating Chunking Strategies](https://research.trychroma.com/evaluating-chunking) : Research on evaluating different chunking strategies for document processing.
- [Gemini Embeddings Documentation](https://ai.google.dev/gemini-api/docs/embeddings) : Documentation on Gemini embeddings, which are mentioned as effective in the content.
- [Cohere Reranker](https://cohere.com/rerank) : Documentation on Cohere reranker, which is mentioned as a tool for boosting performance.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG)]]

![[topics/Concept/Reranking)]]

![[topics/Concept/Contextual BM25)]]

![[topics/Concept/Prompt Caching)]]

![[topics/Concept/Contextual Embeddings)]]

![[topics/Concept/Contextual Retrieval)]]