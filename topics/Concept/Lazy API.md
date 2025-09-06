---
type: Concept
---

The Lazy API in Polars is a powerful feature that allows users to specify a sequence of operations without immediately executing them. Instead, these operations are saved as a computational graph and only run when explicitly called. This approach enables Polars to optimize queries before execution, catch schema errors before processing, and perform memory-efficient queries on large datasets that do not fit into memory. The core object within the Lazy API is the LazyFrame, which can be created from various data sources. The Lazy API is particularly useful for processing large datasets stored in files or databases, as it minimizes the amount of data read into memory and optimizes both memory usage and computation time.