---
already_read: true
link: https://youtube.com/watch?v=zyn_T5uragA&is=sXze75w7_csHTmxT
read_priority: 0
relevance: 5
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-09-29'
---

https://youtube.com/watch?v=zyn_T5uragA&is=sXze75w7_csHTmxT

## Summary

Vortex is a new, highly extensible, open-source columnar file format designed for high-throughput, GPU-native data processing, addressing limitations in Parquet and other formats.

**Motivation & Context**
- Hardware shifts (heterogeneous compute, GPUs, NVMe vs. object storage) demand new data formats optimized for bandwidth and low-latency access.
- Parquet is mature but slow to evolve, with poor random access, metadata overhead for wide tables, and slow compression (e.g., Zstandard).
- Existing formats (Iceberg, Arrow) solve partial problems: Iceberg handles metadata/versioning, Arrow is in-memory only.
- Industry trend: Tech orgs build custom formats (e.g., Meta’s Nimble, Microsoft’s Amodi) for specialized performance gains.

**Vortex Design Goals**
- **Extensibility**: Modular components (encodings, layouts, compute) to avoid calcification and enable future-proofing.
- **Performance**: Targets 100x faster random access, faster scans/writes, and competitive size vs. Parquet.
- **GPU/CPU SIMD Optimization**: Lightweight encodings (e.g., FastLanes, ALP, FSST) avoid data dependencies for efficient random access and GPU compute.
- **Interoperability**: Arrow-native, with bindings for Python, Java, C++, and integrations with DuckDB, DataFusion, Spark.

**Core Concepts**
- **Logical Types**: Decouple physical (Arrow) and logical types (e.g., UTF8, 32-bit int) to support cascaded compression.
- **Arrays**: Lazy, compressed representations of data (e.g., bit-packed, dictionary-encoded) that defer computation.
- **Layouts**: Self-describing structures for organizing data buffers (e.g., row groups, zone maps, bloom filters) out-of-memory.
- **Compute Pushdown**: Filter/projection expressions are pushed into the file format’s logical plan, minimizing I/O and compute.
- **Extension Points**: Custom encodings, layouts, logical types, and compute kernels can be added.

**Default Components**
- **Encodings**: FastLanes (bit-packing, delta, etc.), ALP, FSST, dictionary, Zstandard (for size optimization).
- **Compressor**: Encoding selection strategy (inspired by Better Blocks) with alternatives like "Compact" (PCODC + Zstandard).
- **Layout Strategy**: ClickHouse-inspired, with pages (1MB uncompressed) grouped into stripes (2MB compressed).

**File Format Structure**
- Minimal: Data pages + postscript (offsets/lengths, schema, statistics) + 8-byte EOF marker (version + postscript length).
- Postscript is self-contained, enabling compression/encryption, and supports future format evolution.
- **Self-Describing**: Layouts define byte ranges, enabling flexible organization (e.g., columnar, interleaved, row groups).

**Performance Highlights**
- **Random Access**: 137x faster than Zstandard-compressed Parquet (NVMe, sparse row lookups).
- **Write Throughput**: ~5x faster than Parquet (geometric mean across datasets).
- **Scan Throughput**: ~18x faster than Parquet for full scans.
- **Size**: Geometric mean 1.16x Parquet (varies by dataset: 0.5x–1.5x).
- **ClickBench**: Outperforms all other formats; DuckDB + Vortex faster than DuckDB’s native format.
- **GPU Workloads**: 2x faster than MosaicML’s custom format for GPU data loading; supports CUDA/JIT compilation for kernel compatibility.

**Benchmarking & Validation**
- Continuous benchmarking on AWS (NVMe/EBS) for every commit/PR.
- Comparisons against Parquet, Lance, DuckDB native, and others.
- Real-world use cases: 10x P99 query speedup for a DataFusion API, 30% runtime reduction in Spark TPCH.

**Ecosystem & Adoption**
- Linux Foundation project (incubating, alongside Delta Lake).
- Used in research (AnyBlocks, LiquidCache) and industry (startups, MosaicML).
- Open to contributions, especially for GPU kernels, new encodings, and IO optimizations.

**Future Directions**
- Support for multimodal data (e.g., video metadata + externalized payloads).
- WASM for forward compatibility (e.g., F3’s approach) to embed new encodings without breaking old readers.
- Research collaborations (e.g., sponsoring PhD work on IO optimizations).

## Links



## Topics

![[topics/Library/DataFusion]]

![[topics/Concept/Parquet]]

![[topics/Model/FastLanes]]

![[topics/Concept/Columnar Storage and Processing]]

![[topics/Concept/GPU Accelerated Data Processing]]

![[topics/Concept/Extensible File Formats]]

![[topics/Tool/Vortex]]

![[topics/Library/DuckDB]]

![[topics/Library/Apache Arrow]]

![[topics/Platform/Apache Iceberg]]