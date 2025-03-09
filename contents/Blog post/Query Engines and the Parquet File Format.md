---
already_read: false
link: https://duckdb.org/2025/01/22/parquet-encodings?ref=blef.fr
read_priority: 4
relevance: 0
source: Blef
tags:
- Data_Engineering
type: Content
upload_date: '2025-03-09'
---

https://duckdb.org/2025/01/22/parquet-encodings?ref=blef.fr
## Summary

Mainstream query engines struggle to read newer Parquet encodings, leading systems like DuckDB to default to older encodings, which compromises compression efficiency. Apache Parquet is a column-oriented data storage format optimized for efficient querying, allowing selective reading of columns and utilizing lightweight compression. While Parquet is widely adopted, its evolution requires backward compatibility, ensuring older files remain readable.

DuckDB has implemented several new encodings (e.g., DELTA_BINARY_PACKED, BYTE_STREAM_SPLIT) but will not write them by default to maintain compatibility with other query engines. Compression methods like Snappy and zstd show significant improvements in file size and writing speed when using newer encodings, although real-world data may not always compress as effectively.

A considerable amount of data written in Parquet is wasted due to the lack of support for newer encodings by many query engines. Implementing these encodings could reduce storage needs and improve efficiency in data centers. The article emphasizes the shared responsibility of query engine developers to enhance Parquet's utility by adopting these features.
## Links

1. [Apache Parquet Documentation](https://parquet.apache.org/docs/file-format/data-pages/encodings/) - Official documentation on the Parquet file format, including details on encodings and how they work.
2. [DuckDB GitHub Repository](https://github.com/duckdb/duckdb) - The source code and development repository for DuckDB, useful for understanding its implementation and features.
3. [Delta Lake](https://delta.io) - A storage layer that brings ACID transactions to Apache Spark and big data workloads, often used in conjunction with Parquet.
4. [Robustness Principle](https://en.wikipedia.org/wiki/Robustness_principle) - A principle that can be applied to the design of query engines and data formats, relevant to the discussion of backward compatibility in Parquet.
5. [Snappy Compression](https://github.com/google/snappy) - Information on Snappy, a fast compression and decompression library, which is relevant to the compression methods discussed in the context of DuckDB and Parquet.
## Topics

![](topics/Concept/Apache%20Parquet)

![](topics/Library/DuckDB)

![](topics/Concept/Backward%20Compatibility)

![](topics/Concept/Data%20Compression)

![](topics/Concept/Parquet%20Encodings)