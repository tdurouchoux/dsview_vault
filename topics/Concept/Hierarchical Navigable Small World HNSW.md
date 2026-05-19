---
type: Concept
---

HNSW (Hierarchical Navigable Small World) is a graph-based algorithm and indexing technique for Approximate Nearest Neighbor Search (ANN) that constructs a multi-layered graph structure to enable efficient and scalable similarity search. Each layer of the graph acts as a navigable small-world network, allowing for quick traversal to the nearest neighbors. HNSW is known for its superior performance in terms of search speed and memory usage compared to traditional methods like KD-Trees or Locality Sensitive Hashing (LSH), though it may have higher memory requirements and slower index creation times. It is widely used for vector similarity search and is implemented in libraries like USearch and FAISS.