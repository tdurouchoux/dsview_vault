---
already_read: false
link: https://tembo.io/blog/operationalizing-vectordbs-on-postgres
read_priority: 1
source: null
tags:
- Data_Engineering
- Natural_Language_Processing
type: Content
upload_date: '2024-04-29'
---

https://tembo.io/blog/operationalizing-vectordbs-on-postgres
## Summary

Vector databases are essential for efficiently storing, indexing, and searching embeddings, which are arrays of floats generated from source data. The process of generating embeddings is ongoing, requiring consistent transformations during both training and inference phases to ensure reliable model outputs.

Key points include:

- **Consistency**: The same preprocessing and transformer model must be used for both generating embeddings and querying them to maintain reliability.
- **pg_vectorize**: This tool tracks the transformer model used for each job, facilitating the generation and searching of embeddings. It allows for real-time or scheduled updates to embeddings as source data changes.
- **Implementation**: Developers can create tables for embeddings and perform searches using SQL commands. The system supports various transformer models from OpenAI and Hugging Face.
- **Flexibility**: Users can easily switch transformer models and manage embeddings through a straightforward SQL interface.
- **Future Developments**: Ongoing improvements to pg_vectorize and the VectorDB Stack are planned, including support for additional embedding models and a more comprehensive RAG API.

Overall, operationalizing vector databases involves continuous management of the embedding lifecycle, ensuring that data transformations remain consistent and efficient.
## Links

1. [pg_vectorize GitHub Repository](https://github.com/tembo-io/pg_vectorize) - The official repository for pg_vectorize, an extension for PostgreSQL that helps manage vector databases and embeddings.
2. [Hugging Face Sentence Transformers](https://huggingface.co/sentence-transformers) - A collection of pre-trained models for generating sentence embeddings, useful for various NLP tasks.
3. [OpenAI Embeddings Documentation](https://platform.openai.com/docs/guides/embeddings) - Official documentation on how to use OpenAI's embedding models for generating and utilizing embeddings in applications.
4. [Hugging Face Models](https://huggingface.co/models) - A comprehensive repository of various models available on Hugging Face, including those for generating embeddings.
5. [Tembo Cloud Getting Started](https://tembo.io/docs/product/stacks/ai/vectordb/getting-started) - A guide to getting started with VectorDB on Tembo Cloud, including setup and usage instructions.
## Topics

![](topics/Product/pg_vectorize)

![](topics/Concept/Vector%20Databases)

![](topics/Model/all%20MiniLM%20L6%20v2)

![](topics/Model/text%20embedding%20ada%20002)

![](topics/Platform/Tembo%20Cloud)