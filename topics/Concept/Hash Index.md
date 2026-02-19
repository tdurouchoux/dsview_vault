---
type: Concept
---

The hash index in PostgreSQL is a data structure that uses a hash function to map keys to their corresponding data locations. It is particularly effective for equality comparisons and is much smaller than B-tree indexes, especially for longer data types like UUIDs and URLs. Hash indexes allow direct access to bucket pages, potentially reducing index access time in larger tables. However, they only support equality operations and do not support ordering or multi-column indexes. They are most suited to unique or mostly unique data and can be faster for reads under the right conditions.