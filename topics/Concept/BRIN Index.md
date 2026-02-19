---
type: Concept
---

The BRIN (Block Range Index) is a type of index in PostgreSQL that stores the minimum and maximum values of a range of values present in the page referred by the index. This makes the index more compact and cache-friendly but restricts its use cases. BRIN indexes are particularly effective for append-only tables and tables storing time series data. They are optimized for sequential scans of large amounts of data and are a good optimization to try before partitioning a table. However, they are not suitable for tables where rows are updated constantly due to the nature of MVCC, which can affect the correlation and reduce the effectiveness of the index.