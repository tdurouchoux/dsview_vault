---
type: Concept
---

Data compression refers to the process of encoding information using fewer bits than an unencoded representation, reducing the size of data files for efficient storage and transmission. In the context of Parquet files, compression algorithms such as SNAPPY, GZIP, and ZSTD are used to balance file size reduction with decoding performance. These algorithms can be configured per-column, impacting storage costs and query efficiency. Tools like parquet-linter analyze and optimize compression settings for Parquet files.