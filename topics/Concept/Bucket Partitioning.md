---
type: Concept
---

Bucket partitioning is a technique for distributing data across multiple files based on a hash of a column value. It is useful for columns with high cardinality where traditional partitioning is impractical. Bucket partitioning improves query performance by enabling partition pruning, where only relevant files are scanned. DuckLake supports Iceberg-compatible bucket partitioning using the Murmur3 hash function.