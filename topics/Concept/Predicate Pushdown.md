---
date: '2025-07-19'
type: Concept
---

Predicate pushdown is an optimization technique used in query execution where conditions are pushed down to the storage layer. This allows query engines to filter data at the file or row group level, minimizing the amount of data that is read into memory. By leveraging this technique, data processing frameworks can significantly enhance performance by reducing I/O operations and speeding up query response times.