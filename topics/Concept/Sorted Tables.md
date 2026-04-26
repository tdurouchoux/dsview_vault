---
type: Concept
---

Sorted tables in a lakehouse format store data in a specific order (e.g., by a column or expression) to optimize query performance. Sorting improves read efficiency by enabling techniques like row group pruning and file pruning, which reduce the amount of data scanned during queries. DuckLake supports sorting tables during compaction, flushing, or insertion.