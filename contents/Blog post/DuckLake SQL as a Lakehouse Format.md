---
already_read: false
link: https://duckdb.org/2025/05/27/ducklake.html
read_priority: 5
relevance: 0
source: null
tags:
- Data_Engineering
- Data_Analysis
type: Content
upload_date: '2025-05-28'
---

https://duckdb.org/2025/05/27/ducklake.html
## Summary

DuckLake is a new open table format that simplifies Lakehouses by using a standard SQL database for metadata management, while storing data in open formats like Parquet. This approach makes it more reliable, faster, and easier to manage compared to existing formats like Iceberg and Delta Lake.

Key points:

1. **Background**: DuckLake addresses the limitations of existing Lakehouse formats, which require complex file-based systems for metadata management and lack transactional guarantees.

2. **DuckLake Architecture**: DuckLake stores all metadata in a SQL database, which supports ACID operations and primary keys. This allows for efficient and effective management of metadata needed to support changes in a database. The actual data is stored in open formats like Parquet on blob storage.

3. **Principles**:
   - **Simplicity**: DuckLake is easy to set up and use, with minimal additional software stack required beyond the SQL database.
   - **Scalability**: DuckLake separates storage, compute, and metadata management, allowing each to scale independently.
   - **Speed**: DuckLake reduces the number of small files written to storage and improves conflict resolution, leading to faster performance.

4. **Features**: DuckLake supports a wide range of features, including arbitrary SQL, data changes, multi-schema and multi-table management, complex types, schema evolution, time travel, incremental scans, views, partitioning, and encryption.

5. **DuckLake Extension**: The ducklake extension for DuckDB implements the DuckLake format and supports all its features. It can be used with various storage systems and SQL databases.

6. **Installation and Usage**: The extension can be installed and used with DuckDB, allowing for easy management of DuckLake tables and data.

7. **Press Inquiries**: For press inquiries, contact Gabor Szarnyas.

The article concludes by encouraging readers to try DuckLake for simple, scalable, and fast Lakehouse data management. The ducklake extension is currently experimental, and users are encouraged to report any bugs.
## Links

- [DuckLake Manifesto](https://ducklake.select/manifesto) : The manifesto of DuckLake, explaining the vision and principles behind the project.
- [DuckDB GitHub Repository](https://github.com/duckdb/duckdb) : The official GitHub repository for DuckDB, where you can find the source code, issues, and contributions.

## Topics

![[topics/Concept/Parquet]]

![[topics/Library/Apache Iceberg]]

![[topics/Concept/Lakehouse]]

![[topics/Concept/Delta Lake]]

![[topics/Tool/DuckLake]]