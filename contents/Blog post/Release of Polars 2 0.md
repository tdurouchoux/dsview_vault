---
already_read: true
link: https://pola.rs/posts/release-polars-2/
read_priority: 0
relevance: 5
source: Data Elixir
tags:
- Data_Engineering
type: Content
upload_date: '2026-10-15'
---

https://pola.rs/posts/release-polars-2/

## Summary

Polars 2.0 introduces major performance improvements, first-class SQL support, out-of-core processing, a new Map dtype, and stricter type handling.

**Key Features**
- Out-of-core (spill-to-disk) support enabled by default, starting at ~80% RAM usage with a 64GB disk budget.
- Streaming engine now default for `collect()` on LazyFrame, improving memory/performance but may alter row order for certain operations (opt-in via `maintain_order=True`).
- First-class SQL support with optimizer improvements (join reordering, common-subplan-elimination, dynamic predicates/bloom filters).

**Performance Benchmarks**
- Outperforms DuckDB (1.5.6, 2.0 alpha) and DataFusion (54.0.0) in TPC-H/TPC-DS benchmarks on c7a.4xlarge (16 vCPUs) and c7a.metal (192 vCPUs).
- Scales well with more cores: 3.8x faster on TPC-H (SF100) and 2.2x on TPC-DS when moving from 16 to 192 vCPUs.
- Constant overhead at high thread counts hurts small-data queries; 32-core limit is competitive/winning in all benchmarks.

**New Data Types & Strictness**
- New `Map` dtype (Arrow `MapType`) with dictionary-like methods (key lookups, `.get()`, `.contains_key()`, etc.).
- Stricter dtype handling and explicitness for faster feedback, especially useful for AI-driven development (e.g., `collect_schema()` for early validation).

**Roadmap**
- Planned improvements: better out-of-core (joins/group-bys), scaling at high CPU counts, and GeoPolars.
- Migration guide available for upgrading to 2.0.

## Links

- [Polars Python API Reference](https://docs.pola.rs/py-polars/html/reference/) : Comprehensive reference documentation for the Polars Python API, covering all available functions, classes, and methods in the Polars library. Useful for understanding how to use Polars 2.0 features programmatically.
- [Polars User Guide](https://docs.pola.rs/user-guide/) : Detailed user guide for Polars, including tutorials, best practices, and explanations of core concepts. Essential for learning how to use Polars 2.0 effectively.
- [Polars 2.0 Upgrade Guide](https://docs.pola.rs/releases/upgrade/2/) : Migration guide for upgrading to Polars 2.0, detailing breaking changes, new features, and steps to transition from previous versions. Critical for users planning to adopt Polars 2.0.
- [Polars GitHub Repository](https://github.com/pola-rs/polars/) : Official GitHub repository for the Polars project, containing the source code, issue tracker, and release notes. Useful for exploring the implementation, contributing, or reporting issues.
- [Polars 2.0 Benchmark Repository](https://github.com/pola-rs/polars-2.0-benchmark) : Repository containing benchmarks and performance comparisons for Polars 2.0 against other engines like DuckDB and DataFusion. Provides insights into the performance improvements and scalability of Polars 2.0.


## Topics

![[topics/Concept/TPC H Benchmark]]

![[topics/Concept/Out of core processing]]

![[topics/Concept/Map dtype]]

![[topics/Library/Polars]]

![[topics/Library/DuckDB]]

![[topics/Library/DataFusion]]

![[topics/Concept/TPC DS]]

![[topics/Model/Streaming Engine]]