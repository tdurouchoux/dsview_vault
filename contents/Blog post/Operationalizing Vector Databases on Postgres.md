---
already_read: false
link: https://tembo.io/blog/operationalizing-vectordbs-on-postgres
read_priority: 1
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2024-04-29'
---

https://tembo.io/blog/operationalizing-vectordbs-on-postgres
## Summary

Vector databases are essential for efficiently storing, indexing, and searching embeddings, which are arrays of floats generated from source data. The process of generating embeddings is ongoing, requiring consistent transformations during both training and inference phases to ensure model reliability.

Key points include:

- **Consistency**: The same preprocessing and transformer model must be used for both generating embeddings and querying them to maintain accuracy.
- **pg_vectorize**: This tool tracks which transformer model was used for each job, facilitating the generation and searching of embeddings.
- **Implementation**: Developers can create tables for embeddings and perform searches using SQL commands, with options for real-time or scheduled updates to embeddings.
- **Flexibility**: Users can easily switch between different transformer models, including those from OpenAI and Hugging Face, to adapt to new developments in embedding technology.
- **Direct Transformation**: The system allows for direct transformation of text into embeddings, enabling complex queries and joins.

Future improvements for pg_vectorize and the VectorDB Stack are planned, including support for additional embedding models and enhanced APIs. The project is open-source and available on GitHub, encouraging community engagement and contributions.
## Links

1. [pg_vectorize](https://github.com/tembo-io/pg_vectorize) - Open-source extension for PostgreSQL that helps manage vector embeddings.
2. [Hugging Face Sentence Transformers](https://huggingface.co/sentence-transformers) - A library for state-of-the-art sentence embeddings.
3. [OpenAI Embedding Models](https://platform.openai.com/docs/guides/embeddings) - Documentation on how to use OpenAI's embedding models for various applications.
4. [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) - A specific transformer model for generating embeddings, available on Hugging Face.
5. [Detailed Guide for VectorDB](https://tembo.io/docs/product/stacks/ai/vectordb/getting-started) - A comprehensive guide to getting started with VectorDB and pg_vectorize.
## Topics

- [[topics/Library/pgvector and pg_vectorize]]
- [[topics/Model/all-MiniLM-L6-v2]]
- [[topics/Model/text-embedding-ada-002]]
- [[topics/Platform/Tembo Cloud]]
- [[topics/Concept/Embedding and Embedding Lifecycle]]