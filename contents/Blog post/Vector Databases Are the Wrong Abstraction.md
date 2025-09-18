---
already_read: true
link: https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/
read_priority: 4
relevance: 0
source: Data Science Weekly
tags:
- AI_agent
- Natural_Language_Processing
type: Content
upload_date: '2024-11-01'
---

https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/
## Summary

The content discusses the limitations and complexities of current vector database abstractions and proposes a new approach called "vectorizers" to simplify AI application development. Key points include:

1. **Problem with Vector Databases**: Vector databases treat embeddings as independent data, leading to complex synchronization issues and maintenance costs. Teams often juggle multiple databases and face challenges like stale embeddings and data inconsistencies.

2. **Vectorizers as a Solution**: Vectorizers treat embeddings as derived data, similar to database indexes. This approach automatically keeps embeddings in sync with source data, reducing manual effort and potential errors.

3. **Advantages of Vectorizers**:
   - Automatic synchronization of embeddings with source data.
   - Reinforced relationship between data and embeddings.
   - Simplified data management and reduced cognitive load for developers.

4. **Implementation in PostgreSQL**: The pgai Vectorizer, an open-source tool, implements the vectorizer abstraction in PostgreSQL. It works with pgvector and pgvectorscale extensions for vector search.

5. **How pgai Vectorizer Works**:
   - Developers define vectorizers in SQL, specifying the table, embedding model, chunking, and formatting rules.
   - The system asynchronously creates and updates embeddings, handling inserts, updates, and deletes.
   - Embeddings are created externally to reduce database load and can be customized for different models and chunking strategies.

6. **Benefits of pgai Vectorizer**:
   - Automates embedding management, freeing developers to focus on core tasks.
   - Integrates with other PGAI suite tools for enhanced AI development in PostgreSQL.
   - Offers flexibility in deployment options, including Timescale Cloud and self-hosted environments.

The post encourages trying pgai Vectorizer in Early Access and provides additional resources for learning more about its capabilities and implementation.
## Links

- [pgai Vectorizer Documentation](https://github.com/timescale/pgai/blob/main/docs/vectorizer.md) : Documentation for pgai Vectorizer, an open-source tool for managing vector embeddings in PostgreSQL.
- [Which OpenAI Embedding Model Is Best for Your RAG App With Pgvector?](https://www.tigerdata.com/blog/which-openai-embedding-model-is-best/) : A blog post discussing the best OpenAI embedding models for RAG applications using Pgvector.
- [TigerData Discord Community](https://discord.gg/KRdHVXAmkp) : Join the TigerData Discord community for support and discussions on pgai Vectorizer and other tools in the PGAI suite.
- [What If Vector Embeddings Were Database Indexes?](https://www.youtube.com/watch?v=j2B5fx1p1Ps) : A video explaining the concept of treating vector embeddings as database indexes.
- [How to Automatically Create & Update Embeddings in PostgreSQL](https://www.tigerdata.com/blog/how-to-automatically-create-update-embeddings-in-postgresql/) : A blog post explaining how to automatically create and update embeddings in PostgreSQL using pgai Vectorizer.

## Topics

![[topics/Concept/Retrieval Augmented Generation RAG)]]

![[topics/Concept/Text Chunking)]]

![[topics/Concept/Vector Database)]]

![[topics/Concept/Embedding Models)]]

![[topics/Tool/pgvector)]]

![[topics/Tool/pgvectorscale)]]

![[topics/Tool/pgai Vectorizer)]]

![[topics/Concept/Vectorizers)]]