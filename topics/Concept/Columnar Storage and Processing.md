---
type: Concept
---

A data architecture and processing technique where data is stored and processed column-wise rather than row-wise, enabling efficient compression, selective data access, and high-performance analytical queries. This approach reduces the amount of data read during scans, improves cache utilization, and accelerates aggregations and filtering operations. It is foundational to modern data lakes and analytics systems, with formats like Parquet, Iceberg, and Vortex optimizing for factors such as compression ratio, scan speed, and interoperability. Columnar storage and processing is contrasted with row-based formats (e.g., CSV) and is critical for handling large-scale, heterogeneous data in analytical workloads.