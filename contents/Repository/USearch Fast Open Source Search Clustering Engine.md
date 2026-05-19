---
already_read: true
link: https://github.com/unum-cloud/usearch
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-05-19'
---

https://github.com/unum-cloud/usearch
## Summary

USearch is a high-performance, open-source similarity search and clustering engine supporting vectors and arbitrary objects across multiple languages (C++, Python, JavaScript, Java, Rust, etc.). Key technical highlights:

- **Performance**: 10x faster HNSW implementation than FAISS, optimized with SIMD, Arm SVE, and x86 AVX-512.
- **Flexibility**: Supports user-defined metrics (e.g., Tanimoto, Haversine), custom bindings, and hardware-agnostic quantization (bf16, e5m2, i8).
- **Efficiency**: Memory-mapped files for disk-based indexes, uint40_t for 4B+ entries, and 20x cost reduction on cloud servers.
- **Features**: Near-real-time clustering, semantic joins, predicate filtering, and multi-index lookups.
- **Compatibility**: Works with SQLite, OpenMP, and integrates with tools like ClickHouse, DuckDB, and LangChain.
- **Use Cases**: Semantic search (e.g., text-to-image), molecular search (RDKit), GIS (Haversine/Vincenty distances).

API example in Python:
```python
from usearch.index import Index
index = Index(ndim=3, metric='cos')
index.add(42, [0.2, 0.6, 0.4])
matches = index.search([0.2, 0.6, 0.4], 10)
```

Licensed under Apache-2.0. GitHub: [unum-cloud/USearch](https://github.com/unum-cloud/USearch).
## Links

- [USearch Python Documentation - User-Defined Metrics and JIT Compilation](https://unum-cloud.github.io/USearch/python#user-defined-metrics-and-jit-in-python) : Focuses on advanced Python-specific features like user-defined metrics and JIT compilation, which are critical for customizing USearch in Python applications.
- [USearch C++ Documentation](https://unum-cloud.github.io/USearch/cpp) : Provides core C++11 implementation details, API references, and performance optimizations, essential for C++ developers.
- [ClickHouse USearch Integration Documentation](https://clickhouse.com/docs/en/engines/table-engines/mergetree-family/annindexes#usearch) : Details how USearch is integrated into ClickHouse for efficient vector search, highly relevant for database users.
- [USearch Rust Documentation](https://unum-cloud.github.io/USearch/rust) : Covers Rust-specific API usage and examples, valuable for Rust developers integrating USearch.
- [USearch Performance Benchmarks and Hardware Acceleration](https://ashvardanian.com/posts/gcc-12-vs-avx512fp16/) : Discusses performance benchmarks and hardware acceleration techniques, critical for optimizing USearch deployments.

## Topics

![[topics/Library/USearch]]

![[topics/Concept/Approximate Nearest Neighbor ANN]]

![[topics/Concept/Hierarchical Navigable Small World HNSW]]

![[topics/Concept/User Defined Metrics]]

![[topics/Concept/Quantization]]

![[topics/Concept/Semantic Search]]

![[topics/Concept/Fuzzy Search]]

![[topics/Concept/Multi Index Lookups]]

![[topics/Concept/Clustering]]