---
type: Concept
---

Vectorized processing, also referred to as vectorized execution, is a technique in query processing and data manipulation where operations are applied to batches of data (vectors) or entire columns at once, rather than row by row. This approach leverages SIMD (Single Instruction, Multiple Data) capabilities of modern processors to improve performance by reducing overhead and enabling efficient use of CPU cache. It is particularly effective in columnar data formats, enhancing throughput and reducing latency for analytical workloads.