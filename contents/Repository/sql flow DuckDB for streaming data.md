---
already_read: false
link: https://github.com/turbolytics/sql-flow
read_priority: 3
relevance: 0
source: Data Elixir
tags:
- Data_Engineering
- Data_Analysis
type: Content
upload_date: '2025-05-07'
---

https://github.com/turbolytics/sql-flow
## Summary

SQLFlow is a high-performance stream processing engine that allows users to define data pipelines using SQL. It is built on DuckDB and Apache Arrow for high-speed processing. Key features include:

- **Input Sources**: Kafka, WebSockets, and more.
- **Output Sinks**: PostgreSQL, Kafka topics, cloud storage (e.g., S3), in formats like Parquet and Iceberg.
- **Core Components**: Input Source, Handler (using DuckDB and Apache Arrow for SQL execution), and Output Sink.
- **Use Cases**: Streaming data transformations, stream enrichment, data aggregation, tumbling window aggregation, running SQL against webhook sources, streaming data to Iceberg, enriching streams with PostgreSQL data, and sinking Kafka to PostgreSQL.
- **Features & Roadmap**: Supports various sources, sinks, serialization formats, handlers, and table managers. Includes observability metrics (Prometheus).
- **Performance**: Benchmarks show high throughput and efficient memory usage for different test scenarios.

SQLFlow is designed to simplify building data pipelines with SQL, making it a lightweight, modern alternative to tools like Flink.
## Links

- [SQLFlow Documentation](https://sql-flow.com/docs/tutorials/intro) : Official documentation for SQLFlow, providing tutorials and introductory guides on how to use the stream processing engine.
- [Apache Arrow](https://arrow.apache.org/) : Website for Apache Arrow, a cross-language development platform for in-memory data, which SQLFlow uses for high-speed processing.
- [DuckDB](https://duckdb.org/) : Website for DuckDB, an in-process SQL OLAP database management system, which SQLFlow embeds for high performance.
- [Apache Kafka](https://kafka.apache.org/) : Website for Apache Kafka, a distributed streaming platform that SQLFlow can use as an input source and output sink.
- [PyIceberg](https://py.iceberg.apache.org/) : Website for PyIceberg, a Python library for working with Apache Iceberg, which SQLFlow supports for streaming data to Iceberg tables.

## Topics

![](topics/Library/Apache%20Arrow)

![](topics/Library/pyiceberg)

![](topics/Library/confluent%20kafka)

![](topics/Library/SQLFlow)

![](topics/Library/DuckDB)