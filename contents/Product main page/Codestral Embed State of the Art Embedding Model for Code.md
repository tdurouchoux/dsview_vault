---
already_read: true
link: https://mistral.ai/news/codestral-embed
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Large_Language_Model
- Development_tool
type: Content
upload_date: '2025-05-30'
---

https://mistral.ai/news/codestral-embed
## Summary

- **Codestral Embed**: Mistral AI's new state-of-the-art embedding model specialized for code, outperforming leading models like Voyage Code 3, Cohere Embed v4.0, and OpenAI’s large embedding model.
- **Key Features**:
  - Outputs embeddings with different dimensions and precisions, offering a trade-off between retrieval quality and storage costs.
  - Dimensions are ordered by relevance, allowing for smooth quality-cost trade-offs.
- **Use Cases**:
  - **Retrieval-augmented generation**: Facilitates context retrieval for code completion, editing, or explanation tasks.
  - **Semantic code search**: Enables accurate search of relevant code snippets from natural language or code queries.
  - **Similarity search and duplicate detection**: Identifies near-duplicate or functionally similar code segments.
  - **Semantic clustering and code analytics**: Supports unsupervised grouping of code based on functionality or structure.
- **Availability**:
  - Available on Mistral AI’s API (`codestral-embed-2505`) at $0.15 per million tokens, with a 50% discount on the batch API.
  - On-prem deployments available upon request.
- **Chunking Parameters**:
  - Recommends chunks of 3000 characters with 1000 characters overlap for efficient retrieval.
- **Benchmarks**:
  - Evaluated on various categories including SWE-Bench, Text2Code (GitHub), and Text2SQL, showing superior performance in code retrieval tasks.
## Links

- [Codestral Embed Documentation](https://docs.mistral.ai/capabilities/embeddings/code_embeddings/) : Official documentation for Codestral Embed, providing detailed information on how to use the embedding model for code.
- [Chunking Guide for Retrieval Use Cases](https://docs.mistral.ai/guides/rag/#split-document-into-chunks) : Guide on how to split documents into chunks for retrieval use cases, relevant for optimizing the performance of Codestral Embed.
- [Codestral Embed Cookbook Example](https://colab.research.google.com/github/mistralai/cookbook/blob/main/mistral/embeddings/code_embedding.ipynb) : A practical example in the cookbook showing how to use Codestral Embed for code agent retrieval.

## Topics

![](topics/Model/Codestral%20Embed)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)

![](topics/Concept/Semantic%20Code%20Search)

![](topics/Concept/Similarity%20Search%20and%20Duplicate%20Detection)

![](topics/Concept/Semantic%20Clustering%20and%20Code%20Analytics)

![](topics/Dataset/SWE%20Bench)

![](topics/Dataset/Text2Code%20GitHub)