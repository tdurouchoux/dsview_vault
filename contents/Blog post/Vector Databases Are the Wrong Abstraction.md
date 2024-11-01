---
already_read: true
link: https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/?utm_source=substack&utm_medium=email
read_priority: 4
source: Data Science Weekly
tags:
- Data_Engineering
- Natural_Language_Processing
type: Content
upload_date: '2024-11-01'
---

https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/?utm_source=substack&utm_medium=email
## Summary

The content discusses the limitations of current vector databases in managing AI applications, particularly in the context of retrieval-augmented generation (RAG) systems. It highlights the complexity and risks associated with using multiple databases (e.g., Pinecone, DynamoDB, OpenSearch) to manage embeddings and source data, leading to synchronization issues and potential data inconsistencies.

The authors propose a new abstraction called "vectorizer," which treats embeddings as derived data linked to their source data, similar to how traditional databases manage indexes. This approach simplifies data management by automating the synchronization of embeddings with their source data, reducing the burden on developers.

The pgai Vectorizer, an open-source tool for PostgreSQL, is introduced as a solution to implement this abstraction. It allows developers to create and manage vector embeddings through SQL commands, ensuring that embeddings are automatically updated as the underlying data changes. The tool supports various configurations for chunking, formatting, and indexing, making it adaptable for different use cases.

Key takeaways include:
- Current vector databases create unnecessary complexity by treating embeddings as independent data.
- The vectorizer abstraction simplifies embedding management by linking them directly to source data.
- Pgai Vectorizer for PostgreSQL automates embedding creation and updates, enhancing efficiency in AI application development.
## Links

1. [pgai Vectorizer](https://github.com/timescale/pgai) - An open-source tool for PostgreSQL that automates the creation and updating of vector embeddings, simplifying AI workflows.
2. [pgvector](https://github.com/pgvector/pgvector) - A PostgreSQL extension for storing and searching vector embeddings, enhancing the capabilities of PostgreSQL for AI applications.
3. [pgvectorscale](https://github.com/timescale/pgvectorscale/) - An extension that complements pgvector for high-performance vector search, making it suitable for large-scale AI applications.
4. [How to Automatically Create & Update Embeddings in PostgreSQL — With One SQL Query](https://www.timescale.com/blog/how-to-automatically-create-update-embeddings-in-postgresql/) - A blog post detailing how to manage embeddings efficiently using a single SQL query with pgai Vectorizer.
5. [Which OpenAI Embedding Model Is Best for Your RAG App With Pgvector?](https://www.timescale.com/blog/which-openai-embedding-model-is-best/) - A blog post that helps developers choose the best OpenAI embedding model for their retrieval-augmented generation applications.
## Topics

- [[topics/Library/pgai Vectorizer]]
- [[topics/Library/pgvector and pg_vectorize]]
- [[topics/Library/pgvectorscale]]
- [[topics/Platform/Timescale Cloud]]
- [[topics/Concept/Vectorization Concepts]]