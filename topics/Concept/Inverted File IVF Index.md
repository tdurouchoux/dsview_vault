---
type: Concept
---

The Inverted File (IVF) index, also referred to as IVFFlat when using flat quantization, is a vector indexing method that partitions the vector space into clusters (centroids). During a search, the algorithm identifies the clusters closest to the query vector and evaluates only the vectors within those clusters, significantly reducing the search space. IVF is known for its simplicity, compactness, and efficiency, making it a popular choice for approximate nearest neighbor search in high-dimensional spaces. It offers a lower memory footprint and faster index creation compared to other methods, but requires specifying the number of lists (clusters) upfront, which can impact recall and query performance.