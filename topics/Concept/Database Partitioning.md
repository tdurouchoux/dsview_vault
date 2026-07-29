---
type: Concept
---

Database partitioning is a technique used to divide large tables into smaller, more manageable pieces called partitions. In PostgreSQL, partitioning can be based on values like timestamps or hashes. This approach improves query performance, simplifies data management (e.g., purging old data by dropping partitions), and allows for independent maintenance operations like autovacuum on each partition.