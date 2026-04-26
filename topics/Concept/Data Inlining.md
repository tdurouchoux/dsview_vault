---
type: Concept
---

Data inlining is a technique used in lakehouse formats to store small updates (inserts, deletes, or updates) directly in the catalog database instead of creating new files in object storage. This avoids the 'small file problem' and improves performance for frequent, small updates. In DuckLake, data inlining is enabled by default for operations involving fewer than 10 rows.