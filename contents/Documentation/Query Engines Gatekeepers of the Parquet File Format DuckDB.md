---
already_read: false
link: https://duckdb.org/2025/01/22/parquet-encodings
read_priority: 4
relevance: 0
source: Blef
tags:
- Data_Engineering
type: Content
upload_date: '2025-03-09'
---

https://duckdb.org/2025/01/22/parquet-encodings
## Summary

Mainstream query engines are limited in their support for newer Parquet encodings, resulting in tools like DuckDB defaulting to older encodings, which sacrifices compression efficiency. Parquet is a widely used, column-oriented storage format optimized for efficiency, allowing selective column reading and file size reduction compared to formats like CSV and JSON.

DuckDB aims for backward compatibility so that updated systems can still read previously written Parquet files. Although DuckDB will implement new encodings in version 1.2.0 (DELTA_BINARY_PACKED, DELTA_LENGTH_BYTE_ARRAY, BYTE_STREAM_SPLIT), it will not write these encodings by default to ensure compatibility with mainstream query engines.

The trade-off in compression affects both file size and write times. The new encodings can significantly reduce file sizes, especially with highly compressible data patterns. Despite many TBs of Parquet data being written daily, the lack of support for these newer encodings results in wasted storage. 

The article emphasizes that the effectiveness of Parquet hinges on query engines adopting these features, indicating a shared responsibility among developers to improve Parquet's utility. Implementing newer encodings can lead to substantial savings in storage, impacting the need for physical data center expansion.
## Links

- [Apache Parquet File Format Documentation](https://parquet.apache.org/docs/file-format/data-pages/encodings/) : Official documentation for the Apache Parquet format including details about encodings.
- [Delta Lake](https://delta.io) : A reliable data lake that brings ACID transactions to Apache Spark and big data workloads.
- [Zstandard (zstd) Compression](https://github.com/facebook/zstd) : Zstandard is a fast real-time compression algorithm, providing high compression ratios.
- [DuckDB GitHub Repository](https://github.com/duckdb/duckdb) : The official GitHub repository for DuckDB, which includes code, issues, and pull requests.
- [Robustness Principle - Wikipedia](https://en.wikipedia.org/wiki/Robustness_principle) : An explanation of the Robustness Principle, which guides the design and implementation of software systems.

## Topics

![](topics/Concept/Columnar%20Data%20Storage)

![](topics/Concept/Data%20Interchange%20Format)

![](topics/Library/DuckDB)

![](topics/Concept/Backward%20Compatibility)

![](topics/Concept/Data%20Compression%20Techniques)

![](topics/Concept/Parquet%20Encoding%20Methods)