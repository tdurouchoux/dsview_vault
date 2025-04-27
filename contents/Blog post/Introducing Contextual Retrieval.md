---
already_read: true
link: https://www.anthropic.com/news/contextual-retrieval
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Natural_Language_Processing
- Data_Engineering
type: Content
upload_date: '2024-09-30'
---

https://www.anthropic.com/news/contextual-retrieval
## Summary

The article introduces Contextual Retrieval, an enhancement to Retrieval-Augmented Generation (RAG) aimed at improving AI models' contextual understanding. Traditional RAG often faces issues where context is lost in information retrieval, leading to irrelevant responses. Contextual Retrieval employs two techniques: Contextual Embeddings, which prepend specific context to data chunks, and Contextual BM25, which improves exact match retrieval. This approach decreases failure rates significantly—by 49% in retrieval accuracy and up to 67% when combined with reranking methods.

For smaller knowledge bases (under 200,000 tokens), including the whole database in a single prompt can be efficient. However, as knowledge bases grow, RAG methods become necessary, utilizing embedding models for semantic matching and BM25 for lexical precision.

The article outlines the RAG method’s standard steps: chunking documents, creating vector embeddings, and using a vector database for effective retrieval. It highlights the importance of context in chunks to avoid retrieval misalignment. Methods like contextualization aim to mitigate this by annotating chunks with relevant context before embedding.

Experiments demonstrate that incorporating contextualization improves retrieval rates dramatically across various domains and embedding models. Additional considerations include choosing appropriate chunk sizes, embedding models, and using custom prompts. The performance further enhances through reranking, which filters retrieved chunks by relevance, achieving optimal accuracy with reduced failure rates.

The conclusion emphasizes the synergy of various techniques (embeddings, BM25, contextual retrieval, and reranking) to maximize retrieval performance, urging developers to experiment with these strategies for enhanced results in knowledge base applications.
## Links

- [Anthropic Cookbook on Contextual Embeddings](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/contextual-embeddings) : A resource for implementing contextual embeddings as part of Retrieval-Augmented Generation.
- [Cohere Reranker](https://cohere.com/rerank) : Documentation and information about the Cohere reranking model, used for improving retrieval accuracy.
- [Google Gemini API for Embeddings](https://ai.google.dev/gemini-api/docs/embeddings) : Official Google documentation for using the Gemini API's embedding capabilities.
- [Voyage AI Reranker Documentation](https://docs.voyageai.com/docs/reranker) : Information on using the Voyage AI reranker to enhance retrieval performance in AI applications.
- [Chunking Strategies on Pinecone](https://www.pinecone.io/learn/chunking-strategies/) : A guide discussing various strategies for chunking documents to optimize retrieval processes.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Contextual%20Retrieval)

![](topics/Concept/BM25%20Best%20Matching%2025)

![](topics/Concept/TF%20IDF%20Term%20Frequency%20Inverse%20Document%20Frequency)

![](topics/Tool/Claude)

![](topics/Concept/Embeddings)

![](topics/Concept/Reranking)

![](topics/Concept/Prompt%20Caching)