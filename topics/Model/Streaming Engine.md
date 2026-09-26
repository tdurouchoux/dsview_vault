---
type: Model
---

The streaming engine in Polars is a query execution mode that processes data in chunks, enabling out-of-core computation and reducing memory usage. It is designed to handle large datasets efficiently by streaming data through the query pipeline, often resulting in significant performance improvements (e.g., 5x faster) compared to traditional in-memory engines. The streaming engine is now the default for LazyFrame queries in Polars 2.0.