---
already_read: true
link: https://www.anthropic.com/news/contextual-retrieval
read_priority: 3
source: Alpha Signal
tags:
- Natural_Language_Processing
- Data_Engineering
type: Content
upload_date: '2024-09-30'
---

https://www.anthropic.com/news/contextual-retrieval
## Summary

The article introduces "Contextual Retrieval," a method designed to enhance the effectiveness of AI models in specific contexts by improving the retrieval step in Retrieval-Augmented Generation (RAG). Traditional RAG often loses context when encoding information, leading to less relevant responses. Contextual Retrieval employs two techniques: Contextual Embeddings and Contextual BM25, which together can reduce retrieval failures by up to 67%.

Key points include:

- **Contextual Retrieval**: Enhances retrieval accuracy by adding context to information chunks before embedding and indexing.
- **RAG Overview**: RAG involves breaking down a knowledge base into smaller text chunks, creating embeddings, and using BM25 for precise lexical matching.
- **BM25**: A ranking function that improves retrieval by focusing on exact matches, particularly useful for technical queries.
- **Implementation**: Contextual Retrieval can be implemented using Claude, which allows for efficient context generation without manual annotation.
- **Performance Improvements**: Experiments showed significant reductions in retrieval failure rates when using Contextual Retrieval techniques.
- **Reranking**: Combining Contextual Retrieval with reranking further optimizes retrieval accuracy, reducing failure rates by 67%.
- **Cost and Latency**: While reranking improves performance, it may introduce latency and cost, necessitating a balance based on specific use cases.

Overall, the article encourages developers to experiment with these techniques to enhance the performance of AI models in knowledge retrieval tasks.
## Links

1. [Anthropic Cookbook - Contextual Embeddings](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/contextual-embeddings) - A resource for implementing contextual embeddings in AI models.
2. [Cohere Rerank](https://cohere.com/rerank) - Information on the reranking model that can optimize retrieval accuracy in AI systems.
3. [Voyage AI Documentation - Reranker](https://docs.voyageai.com/docs/reranker) - Documentation on the reranking capabilities offered by Voyage AI.
4. [Chunking Strategies - Pinecone](https://www.pinecone.io/learn/chunking-strategies/) - A guide on effective chunking strategies for knowledge bases.
5. [Gemini API - Embeddings](https://ai.google.dev/gemini-api/docs/embeddings) - Documentation on the Gemini API's embedding capabilities, relevant for improving retrieval accuracy.
## Topics

![](topics/Concept/Contextual%20Retrieval)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Contextual%20Embeddings)

![](topics/Concept/Contextual%20BM25)

![](topics/Product/Claude%20AI)