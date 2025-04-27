---
date: '2024-06-05'
type: Concept
---

The Lazy API in Polars allows users to define a sequence of operations without immediately executing them. This approach creates a computational graph that can be optimized prior to execution, facilitating more efficient processing of queries, especially over large datasets that can't fit into memory, through techniques like predicate pushdown.