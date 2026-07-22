---
type: Tool
---

Apache DataFusion Comet is a high-performance accelerator and subproject of Apache DataFusion designed to enhance the execution speed of Apache Spark queries. It integrates seamlessly with the Apache DataFusion native engine, enabling existing Spark workloads to run faster without requiring code changes. Comet accelerates Parquet scans, particularly for datasets managed by Apache Iceberg, and leverages DataFusion's query engine and optimizations to improve performance. It operates on commodity hardware, ensuring cost-effectiveness and scalability while avoiding the need for specialized accelerators like GPUs or FPGAs.