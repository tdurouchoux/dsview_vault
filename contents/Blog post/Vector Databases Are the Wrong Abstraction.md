---
already_read: true
link: https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/?utm_source=substack&utm_medium=email
read_priority: 4
source: Data Science Weekly
tags:
- Data_Engineering
- AI_regulation
type: Content
upload_date: '2024-11-01'
---

https://www.timescale.com/blog/vector-databases-are-the-wrong-abstraction/?utm_source=substack&utm_medium=email
## Summary

The content discusses the limitations of current vector databases in managing AI applications, particularly in the context of semantic search and retrieval-augmented generation (RAG) systems. It highlights the complexity and risks associated with using multiple databases (e.g., Pinecone, DynamoDB, OpenSearch) to manage embeddings and source data, leading to synchronization issues and potential data inconsistencies.

The authors propose a new abstraction called "vectorizer," which treats embeddings as derived data linked to their source data, similar to how traditional databases manage indexes. This approach simplifies data management by automating the synchronization of embeddings with their source data, reducing the burden on developers.

The implementation of this concept is exemplified through the pgai Vectorizer for PostgreSQL, which allows developers to create and manage vector embeddings directly within the database. This tool automates the embedding process, ensuring that embeddings are always up-to-date and reducing the need for manual intervention.

Key takeaways include:
- Current vector databases create unnecessary complexity by treating embeddings as independent data.
- The vectorizer abstraction simplifies embedding management by linking them directly to source data.
- Pgai Vectorizer for PostgreSQL automates the creation and updating of embeddings, enhancing efficiency for AI applications.
## Links

1. [pgai Vectorizer Documentation](https://github.com/timescale/pgai/blob/main/docs/vectorizer.md?ref=timescale.com) - Detailed documentation on the pgai Vectorizer, which automates the creation and updating of vector embeddings in PostgreSQL.
2. [pgvector Documentation](https://docs.timescale.com/use-timescale/latest/extensions/pgvector/) - Information on the pgvector extension for PostgreSQL, which enables vector search capabilities.
3. [How to Automatically Create & Update Embeddings in PostgreSQL](https://www.timescale.com/blog/how-to-automatically-create-update-embeddings-in-postgresql/) - A blog post explaining how to manage embeddings in PostgreSQL using the pgai Vectorizer.
4. [Which OpenAI Embedding Model Is Best?](https://www.timescale.com/blog/which-openai-embedding-model-is-best/) - A blog post discussing various OpenAI embedding models and their suitability for different applications.
5. [How OpenSauced Is Building a Copilot for Git History With pgvector and Timescale](https://www.timescale.com/blog/how-opensauced-is-building-a-copilot-for-git-history-with-pgvector-and-timescale/) - An article detailing a practical application of pgvector and Timescale in a real-world project.
## Topics

![](topics/Product/pgai%20Vectorizer)

![](topics/Library/pgvector%20and%20pg_vectorize)

![](topics/Library/pgvectorscale)

![](topics/Platform/Timescale%20Cloud)

![](topics/Concept/Vectorizer%20Abstraction)