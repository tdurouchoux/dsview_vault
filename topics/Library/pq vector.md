---
type: Library
---

pq-vector is a proof-of-concept Rust library designed to enable efficient vector search directly within Parquet files. It leverages Parquet's columnar storage and metadata features to implement zero-copy vector indexing and search. The library integrates with DataFusion to provide SQL-based vector search capabilities, allowing users to perform similarity searches without requiring external vector databases. pq-vector focuses on simplicity and compatibility with existing Parquet-based workflows.