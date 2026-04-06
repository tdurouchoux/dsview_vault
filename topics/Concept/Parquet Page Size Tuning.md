---
type: Concept
---

Parquet page size tuning involves configuring the Parquet file format to optimize random access performance for specific use cases, such as vector search. By setting the page size to match the size of individual vector embeddings, each vector is stored in its own compressed page. This allows for efficient retrieval of individual vectors without decompressing large amounts of data, effectively turning Parquet into a random-access-friendly format for vector embeddings.