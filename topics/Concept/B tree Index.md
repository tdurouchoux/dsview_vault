---
type: Concept
---

The B-tree (Balanced Tree) index is a powerful data structure used in PostgreSQL and many other database management systems. It enables efficient searching, insertion, deletion, and range queries. B-tree indexes are balanced, meaning all leaf nodes are at the same level, which ensures consistent performance. They are particularly effective for maintaining O(log n) time complexity for large datasets, making them suitable for primary and unique key constraints. B-tree indexes are the default index type in PostgreSQL and are used extensively for system and TOAST indexes.