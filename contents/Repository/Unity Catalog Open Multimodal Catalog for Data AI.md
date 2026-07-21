---
already_read: true
link: https://github.com/unitycatalog/unitycatalog
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-07-22'
---

https://github.com/unitycatalog/unitycatalog
## Summary

Unity Catalog is an open-source, multi-modal catalog for data and AI assets, supporting formats like Delta Lake, Apache Iceberg, Apache Hudi, Parquet, JSON, and CSV. It offers multi-engine compatibility via open APIs and supports governance for tabular data, unstructured assets, and AI models. Licensed under Apache 2.0, it is compatible with Apache Hive and Iceberg REST APIs, and is a sandbox project under LF AI & Data Foundation.

Key features:
- **Multi-format & multi-engine support**: Extensible for various data formats and compute engines.
- **Unified governance**: Manages data and AI assets with a single interface.
- **Open APIs**: Includes OpenAPI spec and SDKs for integration.

Quickstart:
1. Run the UC server (`bin/start-uc-server`).
2. Use the CLI to list tables (`bin/uc table list --catalog unity --schema default`).
3. Query tables via DuckDB (install `uc_catalog` and `delta` extensions).
4. Access the UI (requires Node.js and Yarn).

Build & deploy:
- Built with sbt (`build/sbt clean package`).
- Deploy via tarball (`build/sbt createTarball`).
- Supports Java 17+ and IDE integration (IntelliJ recommended).

Ecosystem: Backed by major companies (AWS, Google Cloud, NVIDIA, etc.). Roadmap and docs available at [unitycatalog.io](https://unitycatalog.io/). APIs are evolving and not yet stable.
## Links

- [Unity Catalog Official Documentation](https://docs.unitycatalog.io/) : Official documentation for Unity Catalog, providing detailed guides, API references, and usage instructions for the open, multi-modal catalog for data and AI.
- [Unity Catalog REST API Documentation](https://docs.unitycatalog.io/swagger-docs/) : Swagger/OpenAPI documentation for the Unity Catalog REST API, detailing endpoints, request/response structures, and compatibility information.
- [Delta Lake Official Blog](https://delta.io/blog/delta-kernel/) : Official blog post explaining Delta Kernel, a Java library that powers Delta Lake operations, including its integration with Unity Catalog for reading Delta tables.
- [DuckDB Installation Guide](https://duckdb.org/docs/installation/) : Official installation guide for DuckDB, a high-performance in-process analytical database that can interact with Unity Catalog for querying data.
- [LF AI & Data Foundation Projects](https://lfaidata.foundation/projects) : Overview of projects hosted under the LF AI & Data Foundation, including Unity Catalog, which is a sandbox project within this foundation. Provides context about its governance and ecosystem.

## Topics

![[topics/Platform/Unity Catalog]]

![[topics/Concept/Multi modal Data Catalog]]

![[topics/Tool/UniForm]]

![[topics/Library/Delta Kernel]]

![[topics/Concept/OpenAPI Specification]]

![[topics/Tool/UC CLI]]

![[topics/Concept/Data Governance]]