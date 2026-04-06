---
type: Concept
---

Row groups and pages are structural components of Parquet files that significantly influence storage and query performance. A row group is a collection of rows stored together, while a page is a smaller unit within a row group. Tuning these sizes is critical for optimizing Parquet files: smaller row groups and pages can improve parallelism and reduce memory usage during decoding but may increase overhead, while larger sizes reduce metadata overhead but may impact selective query performance. 

In specific use cases like vector search, configuring the page size to match the size of individual vector embeddings allows each vector to be stored in its own compressed page. This enables efficient retrieval of individual vectors without decompressing large amounts of data, effectively transforming Parquet into a random-access-friendly format for vector embeddings.