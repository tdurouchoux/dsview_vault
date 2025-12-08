---
type: Concept
---

Isomap is a non-linear dimensionality reduction technique that extends Multidimensional Scaling (MDS) to capture the geometric structure of data that may not be well-represented by linear techniques like PCA. Isomap constructs a graph that captures the local similarity structure of the data, measures geodesic distances between points in this graph, and then applies MDS to project the data into a lower-dimensional space. This method is particularly effective for data that lies on or near a nonlinear manifold.