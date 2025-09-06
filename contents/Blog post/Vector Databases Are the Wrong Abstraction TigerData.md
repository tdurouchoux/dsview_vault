---
already_read: true
link: https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/
read_priority: 4
relevance: 0
source: Data Science Weekly
tags:
- Natural_Language_Processing
- Development_tool
- Data_Engineering
type: Content
upload_date: '2024-11-01'
---

https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/
## Summary

The content discusses the challenges and complexities of managing vector databases and proposes a new abstraction called "vectorizers" to simplify the process. The authors argue that vector databases treat embeddings as independent data, leading to synchronization issues and increased maintenance costs. They introduce the concept of vectorizers, which treat embeddings as derived data, similar to database indexes, to automatically keep embeddings in sync with their source data. The post details the implementation of this concept in PostgreSQL through an open-source tool called pgai Vectorizer, which integrates with pgvector and pgvectorscale extensions. The tool aims to reduce the burden on developers by automating embedding management, allowing them to focus on building AI applications. The authors encourage readers to try pgai Vectorizer and provide resources for further learning.
## Links

- [pgai Vectorizer Quick Start Guide](https://github.com/timescale/pgai/blob/main/docs/vectorizer-quick-start.md) : Quick start guide for pgai Vectorizer, providing instructions on how to get started with creating and updating vector embeddings in PostgreSQL.
- [pgai Vectorizer Documentation](https://github.com/timescale/pgai/blob/main/docs/vectorizer.md) : Comprehensive documentation for pgai Vectorizer, detailing its features, configurations, and usage for managing vector embeddings in PostgreSQL.
- [pgvector Documentation](https://github.com/pgvector/pgvector/blob/master/README.md) : Documentation for pgvector, an extension for PostgreSQL that enables vector similarity search and other vector operations.

## Topics

![](topics/Tool/pgai%20Vectorizer)

![](topics/Concept/Vectorizer)

![](topics/Concept/Vector%20Embeddings)

![](topics/Concept/Semantic%20Search)

![](topics/Concept/Retrieval%20Augmented%20Generation%20RAG)