---
type: Concept
---

HNSW (Hierarchical Navigable Small World) is an indexing technique used for efficient vector similarity search. It builds a multi-layer graph structure that allows for better recall and more consistent query performance compared to other methods like IVFFlat. However, HNSW has higher memory requirements and slower index creation times, which can be challenging in production environments with large datasets.