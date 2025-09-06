---
already_read: false
link: https://duckdb.org/2025/05/27/ducklake.html
read_priority: 5
relevance: 0
source: null
tags:
- Data_Engineering
- Development_tool
type: Content
upload_date: '2025-05-28'
---

https://duckdb.org/2025/05/27/ducklake.html
## Summary

DuckLake is a new lakehouse format that simplifies data management by using a standard SQL database for metadata, while storing data in open formats like Parquet. This approach improves reliability, speed, and ease of management compared to existing systems like Iceberg and Delta Lake.

Key points:

1. **Background**: DuckLake addresses the limitations of traditional lakehouse formats, which rely on complex file-based systems for metadata management. These systems often struggle with consistency, scalability, and the ability to handle multiple tables efficiently.

2. **DuckLake Architecture**: DuckLake stores all metadata in a SQL database, which supports ACID transactions and primary keys. This design allows for efficient management of table metadata and supports features like cross-table transactions, views, and nested types.

3. **Simplicity**: DuckLake is designed to be simple and incremental. It can be run on a laptop with DuckDB and a local DuckDB file as the catalog store. It supports integration with various storage systems and SQL databases.

4. **Scalability**: DuckLake separates storage, compute, and metadata management, allowing each component to scale independently. It can manage an arbitrary number of tables and supports migration between different SQL databases.

5. **Speed**: DuckLake improves performance by reducing the number of small files written to storage and minimizing the time spent in the critical path of transaction commits. It supports efficient compaction of snapshots and allows for many concurrent transactions.

6. **Features**: DuckLake supports a wide range of features, including arbitrary SQL, data changes, multi-schema and multi-table management, complex types, schema evolution, time travel, incremental scans, views, partitioning, and encryption.

7. **DuckLake Extension**: The ducklake extension for DuckDB implements the DuckLake format and supports all its features. It can be used with various storage systems and SQL databases, including PostgreSQL, SQLite, MySQL, and MotherDuck.

8. **Installation and Usage**: The ducklake extension can be installed and used with DuckDB. It supports basic operations like creating tables, inserting data, and querying tables. It also supports time travel and transactional operations.

In summary, DuckLake offers a simplified, scalable, and fast approach to lakehouse data management by leveraging SQL databases for metadata and open formats for data storage.
## Links

- [DuckLake Manifesto](https://ducklake.select/manifesto) : The manifesto of DuckLake, detailing its principles and vision for a SQL-based lakehouse format.
- [DuckDB GitHub Repository](https://github.com/duckdb/duckdb) : The official GitHub repository for DuckDB, where you can find the source code, issues, and contributions related to DuckDB.

## Topics

![](topics/Concept/Lakehouse)

![](topics/Concept/DuckLake)

![](topics/Concept/Apache%20Iceberg)

![](topics/Concept/Delta%20Lake)

![](topics/Tool/Apache%20Parquet)