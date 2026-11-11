---
type: Model
---

A classic algorithm for solving the k-means clustering problem. It performs full-batch optimization by assigning every point to its nearest centroid and recomputing centroids as the exact mean of all points assigned to them. Each iteration involves a full pass over the dataset, and the process is repeated for a fixed number of iterations. e-means is presented as a modern replacement for Lloyd's algorithm, offering significant speedups and lower loss.