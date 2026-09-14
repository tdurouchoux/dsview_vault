---
already_read: true
link: https://github.com/beowolx/rensa
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-09-14'
---

https://github.com/beowolx/rensa

## Summary

Rensa is a high-performance Rust-based MinHash library with Python bindings for near-duplicate detection and Jaccard similarity estimation.

**Performance**
- 608.52× faster than Datasketch and 11.92× faster than FastSketch in batch benchmarks.
- Uses R-MinHash and C-MinHash with a rho pipeline for bulk filtering.

**Key Features**
- Supports batch and streaming deduplication.
- Compact signatures (512 bytes for 128 slots).
- Incremental sketch updates with consistent results regardless of token order.
- Accepts token iterables (strings, bytes) and prehashed inputs.
- SIMD optimizations (NEON, AVX2, AVX-512) and batch processing in Rust.

**Limitations**
- Estimates similarity (not exact) and may miss duplicates.
- Compares token overlap, not semantic similarity.
- Does not support Weighted MinHash or HyperLogLog.

**Use Cases**
- Near-duplicate detection without pairwise comparisons.
- Batch or streaming document filtering.
- Compact, order-independent signatures.

**Installation**
- `uv add rensa` (requires rebuild for saved signatures from v0.4.x or earlier).

## Links

- [Fast Similarity Sketching (arXiv Paper)](https://arxiv.org/abs/1704.04370) : A research paper introducing the Fast Similarity Sketching technique, which is the foundation for Rensa's R-MinHash implementation. It explains the algorithmic optimizations that enable faster MinHash computations.
- [FastSketchLSH GitHub Repository](https://github.com/pzcddm/FastSketchLSH) : The GitHub repository for FastSketchLSH, a tool mentioned in the benchmarks as a competitor to Rensa. It provides context for performance comparisons and alternative approaches to MinHash-based deduplication.
- [Datasketch Library](https://ekzhu.com/datasketch/) : The official page for the Datasketch library, another MinHash implementation used in the benchmarks. It is relevant for understanding the performance benchmarks and alternative tools in the deduplication space.
- [C-MinHash Paper (PMLR)](https://proceedings.mlr.press/v162/li22m.html) : A paper on C-MinHash, a variant of MinHash implemented in Rensa. It provides theoretical background for the C-MinHash algorithm used in Rensa's deduplication pipeline.


## Topics

![[topics/Library/Rensa]]

![[topics/Model/R MinHash]]

![[topics/Model/C MinHash]]

![[topics/Tool/rho pipeline]]

![[topics/Library/Datasketch]]

![[topics/Library/FastSketch]]

![[topics/Concept/Locality Sensitive Hashing LSH]]

![[topics/Concept/MinHash]]

![[topics/Concept/Jaccard similarity]]