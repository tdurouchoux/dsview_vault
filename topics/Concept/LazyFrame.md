---
type: Concept
---

A LazyFrame in Polars is a symbolic representation of a query plan that has not yet been executed. It enables lazy evaluation, where operations are optimized and executed only when explicitly collected (e.g., via `.collect()`). LazyFrames support predicate pushdown, projection pushdown, and out-of-core processing, making them efficient for large datasets.