---
already_read: true
link: https://datafusion.apache.org/comet/
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-07-22'
---

https://datafusion.apache.org/comet/
## Summary

Apache DataFusion Comet is a high-performance accelerator for Apache Spark that runs existing Spark queries on the Apache DataFusion native engine without requiring code changes. It also accelerates Parquet scans for Apache Iceberg.

Key technical points:
- **Compatibility**: 100% compatible with supported Spark versions; automatically falls back to Spark engine for unsupported features.
- **Performance**: Accelerates queries (e.g., TPC-DS @ 1TB) by leveraging DataFusion’s execution engine.
- **Hardware**: Uses commodity hardware (no GPUs/FPGAs or vendor lock-in).
- **Architecture**: Intercepts Spark physical plans, translates supported operators to DataFusion via protocol buffers.
- **Setup**: Enable via `--jars` and Spark plugin configurations (e.g., `CometPlugin`, `CometShuffleManager`).
- **Resources**: Documentation includes User Guide, Contributor Guide, and Changelog; community support via Slack/Discord. Apache 2.0 licensed.
## Links

- [Comet Benchmarking Guide](https://datafusion.apache.org/comet/contributor-guide/benchmarking.html) : This link provides detailed performance benchmarks, methodologies, and per-query breakdowns for Apache DataFusion Comet, particularly focusing on TPC-DS benchmarking and performance improvements.
- [DataFusion Comet GitHub Repository](https://github.com/apache/datafusion-comet) : The official GitHub repository for Apache DataFusion Comet, offering access to the source code, contribution guidelines, and implementation details for developers and contributors.

## Topics

![[topics/Tool/Apache DataFusion Comet]]

![[topics/Concept/Query Optimization]]

![[topics/Concept/Commodity Hardware]]

![[topics/Concept/Parquet]]

![[topics/Concept/TPC DS]]

![[topics/Library/Apache Spark]]

![[topics/Library/Apache DataFusion]]