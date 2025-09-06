---
already_read: true
link: https://www.anthropic.com/news/contextual-retrieval
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Natural_Language_Processing
- Development_tool
type: Content
upload_date: '2024-09-30'
---

https://www.anthropic.com/news/contextual-retrieval
## Summary

Anthropic introduces Contextual Retrieval, a method to improve the retrieval step in Retrieval-Augmented Generation (RAG) systems. Traditional RAG solutions often fail to retrieve relevant information due to context loss during encoding. Contextual Retrieval uses two sub-techniques: Contextual Embeddings and Contextual BM25, reducing failed retrievals by 49% and up to 67% when combined with reranking.

Key points:
- Contextual Retrieval prepends chunk-specific explanatory context to each chunk before embedding and indexing, enhancing retrieval accuracy.
- For smaller knowledge bases (<200,000 tokens), including the entire knowledge base in the prompt can be a simple and effective solution, especially with prompt caching for efficiency.
- Traditional RAG systems use embeddings and BM25 to retrieve information, but they often lack context, leading to inaccurate or incomplete responses.
- Contextual Retrieval improves performance across various knowledge domains and embedding models, with significant gains in retrieval accuracy.
- Reranking can further optimize retrieval performance by filtering the most relevant chunks, reducing cost and latency.
- Developers can implement Contextual Retrieval using Anthropic's cookbook and leverage prompt caching to reduce costs.

The post concludes that combining contextual embeddings (from Voyage or Gemini) with contextual BM25, plus a reranking step, and adding the top 20 chunks to the prompt maximizes performance improvements in RAG systems.
## Links

- [Contextual Retrieval Appendix 2](https://assets.anthropic.com/m/1632cded0a125333/original/Contextual-Retrieval-Appendix-2.pdf) : Appendix 2 of the Contextual Retrieval document, providing additional data and insights related to the experiments and results discussed in the main article.
- [Evaluating Chunking Strategies](https://research.trychroma.com/evaluating-chunking) : An article discussing various chunking strategies for improving the performance of retrieval-augmented generation systems.
- [Contextual Embeddings Cookbook](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/contextual-embeddings) : A cookbook guide on implementing Contextual Embeddings, a technique used to improve the retrieval step in RAG systems.

## Topics

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Contextual%20Retrieval)

![](topics/Concept/Contextual%20Embeddings)

![](topics/Concept/Contextual%20BM25)

![](topics/Concept/Prompt%20Caching)

![](topics/Concept/Reranking)