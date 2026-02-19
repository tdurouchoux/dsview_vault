---
type: Concept
---

The Generalized Search Tree (GiST) is a balanced tree structure used as a base template to implement indexes for specific data types in PostgreSQL. It is useful for indexing points and geometric types, inet, ranges, and text vectors. GiST indexes allow for the development of non-balanced data structures and are particularly effective for full-text search. They are faster for lookups but are larger and have greater building and maintenance costs compared to other index types. The choice of index type depends on the specific requirements of the application.