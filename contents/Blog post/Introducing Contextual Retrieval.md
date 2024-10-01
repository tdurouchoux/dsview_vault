---
already_read: true
link: https://www.anthropic.com/news/contextual-retrieval
read_priority: 3
source: Alpha Signal
tags:
- Natural_Language_Processing
- Generative_AI
- Data_Engineering
type: Content
upload_date: '2024-09-30'
---

https://www.anthropic.com/news/contextual-retrieval
## Summary

The article introduces "Contextual Retrieval," a method designed to enhance the effectiveness of AI models in specific contexts by improving the retrieval step in Retrieval-Augmented Generation (RAG). Traditional RAG often loses context when encoding information, leading to less relevant responses. Contextual Retrieval employs two techniques: Contextual Embeddings and Contextual BM25, which together can reduce retrieval failures by up to 67%.

Key points include:

- **Contextual Embeddings**: Adds specific context to each chunk of information, improving retrieval accuracy.
- **Contextual BM25**: Combines lexical matching with semantic understanding to ensure precise retrieval of relevant information.
- **RAG Process**: Involves breaking down knowledge bases into smaller chunks, creating embeddings, and using BM25 for exact matches.
- **Performance Improvements**: Contextual Retrieval significantly reduces retrieval failure rates, with experiments showing a 49% reduction when combining both techniques.
- **Reranking**: Further enhances retrieval accuracy by scoring and selecting the most relevant chunks, achieving a 67% reduction in retrieval failures when combined with Contextual Retrieval.
- **Implementation Considerations**: Factors such as chunk size, embedding models, and custom prompts can affect performance.
- **Cost and Latency**: Prompt caching and careful management of reranking can optimize costs and processing times.

The article encourages developers to experiment with these techniques to improve the performance of AI models in handling large knowledge bases.
## Links

1. [our cookbook](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/contextual-embeddings) - A resource for implementing Contextual Retrieval and related techniques.
2. [prompt caching](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching) - Documentation on how to use prompt caching to improve efficiency in AI model interactions.
3. [Cohere reranker](https://cohere.com/rerank) - Information about a reranking model that can enhance retrieval accuracy in AI systems.
4. [Gemini](https://ai.google.dev/gemini-api/docs/embeddings) - Details on the Gemini embedding model, which is noted for its effectiveness in retrieval tasks.
5. [Voyage](https://www.voyageai.com/) - Overview of the Voyage AI platform, which offers tools for embedding and reranking in AI applications.
## Topics

- [[topics/Concept/Contextual Retrieval]]
- [[topics/Concept/Retrieval-Augmented Generation (RAG)]]
- [[topics/Concept/Embeddings]]
- [[topics/Concept/BM25]]
- [[topics/Concept/Reranking]]