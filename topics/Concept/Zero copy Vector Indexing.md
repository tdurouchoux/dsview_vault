---
type: Concept
---

Zero-copy vector indexing refers to the technique of creating and using vector indexes without duplicating the underlying vector data. In this approach, the index only stores lightweight metadata, such as row IDs and cluster centroids, while the actual vector embeddings remain in their original location within the Parquet files. This minimizes storage overhead and avoids the need for data duplication, making vector search more efficient and compatible with standard data formats like Parquet.