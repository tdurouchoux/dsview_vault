---
already_read: true
link: https://ducklake.select/2026/04/13/ducklake-10/
read_priority: 0
relevance: 4
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-04-26'
---

https://ducklake.select/2026/04/13/ducklake-10/
## Summary

DuckLake v1.0 is a production-ready lakehouse format specification built on SQL, with a reference implementation (DuckDB ducklake extension) available in DuckDB v1.5.2. Key features include:

- **Core Concept**: Stores all metadata in a SQL-compatible catalog database (e.g., SQLite, PostgreSQL, or DuckDB), unlike other formats (Delta Lake, Iceberg) that scatter metadata in files.
- **Key Features**:
  - **Data Inlining**: Small updates/deletes (≤10 rows) are stored in the catalog, avoiding small file proliferation.
  - **Sorted Tables**: Improves query performance via row group/file pruning; supports column ordering and SQL expressions.
  - **Bucket Partitioning**: Hash-based partitioning for high-cardinality columns (compatible with Iceberg).
  - **Type System**: Adds `GEOMETRY` (with spatial filter pushdown) and `VARIANT` (binary-encoded, shredded for performance).
  - **Deletion Vectors**: Experimental support for Iceberg v3-compatible deletion vectors (Puffin files).
- **Adoption**: Top-10 DuckDB extension; clients for Spark, Trino, Pandas, and a hosted service by MotherDuck. Used in production at dozens of companies.
- **Future**:
  - **v1.1**: Variant inlining, multi-deletion vector Puffin files.
  - **v2.0**: Git-like branching, role-based permissions, incremental materialized views.
- **Stability**: 108 PRs focused on reliability, performance, and correctness (e.g., concurrency fixes, metadata query logging).
## Links

- [DuckLake v1.0 Release Announcement by MotherDuck](https://motherduck.com/blog/announcing-ducklake-1-0-on-motherduck/) : Official announcement of DuckLake v1.0 support on MotherDuck, a hosted DuckLake service. This link highlights the production-readiness and managed service offering for DuckLake.
- [DuckLake Specification and Documentation](https://ducklake.select/) : The official DuckLake website, providing documentation, specifications, and resources for DuckLake v1.0. This is a primary source for understanding DuckLake's architecture and features.
- [DuckLake GitHub Repository](https://github.com/duckdb/ducklake) : The official GitHub repository for DuckLake, containing the reference implementation, issue tracking, discussions, and contributions. This is a critical resource for developers and contributors.
- [Awesome DuckLake Community Resources](https://github.com/esadek/awesome-ducklake) : A curated list of DuckLake-related tools, libraries, and resources. This repository provides a comprehensive overview of the DuckLake ecosystem, including clients for Apache DataFusion, Spark, Trino, and Pandas.
- [DuckLake Integration Guide for MotherDuck](https://motherduck.com/docs/integrations/file-formats/ducklake/) : A detailed guide on integrating and using DuckLake with MotherDuck's platform. This includes setup instructions, best practices, and examples for leveraging DuckLake in a managed environment.

## Topics

![[topics/Concept/Lakehouse]]

![[topics/Concept/Data Inlining]]

![[topics/Concept/Sorted Tables]]

![[topics/Concept/Bucket Partitioning]]

![[topics/Concept/Deletion Vectors]]

![[topics/Concept/Variant Data Type]]

![[topics/Concept/Geometry Data Type]]

![[topics/Library/DuckDB]]

![[topics/Tool/DuckLake]]