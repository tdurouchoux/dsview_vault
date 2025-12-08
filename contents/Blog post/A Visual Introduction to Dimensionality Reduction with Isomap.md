---
already_read: true
link: https://alechelbling.com/blog/isomap/
read_priority: 0
relevance: 3
source: Data Elixir
tags:
- Dimensionality_reduction
type: Content
upload_date: '2025-12-08'
---

https://alechelbling.com/blog/isomap/
## Summary

The article "A Visual Introduction to Dimensionality Reduction with Isomap" by Alec Helbling discusses the challenges of working with high-dimensional data and introduces Isomap, a non-linear dimensionality reduction technique. The article starts with a simple example of a 1D spiral embedded in 2D space to illustrate the concept of intrinsic dimensionality and the need for dimensionality reduction.

Isomap builds upon the manifold hypothesis and involves three main steps: constructing a graph that captures the local structure of data, measuring geodesic distances between all pairs of points in this graph, and applying multi-dimensional scaling (MDS) to project the high-dimensional data into a lower-dimensional embedding that preserves these distances.

The article explains MDS, which preserves pairwise distances between points, and its equivalence to Principal Component Analysis (PCA) when using Euclidean distance. However, classical MDS with Euclidean distance has limitations, as it only works for data with linear structure.

To address this, Isomap uses a k-nearest neighbor graph to capture local similarity structure and computes shortest path distances between points in the graph. These distances are then used in classical MDS to obtain a low-dimensional embedding that respects the local similarity structure of the data.

The article concludes by noting the limitations of Isomap, such as the impact of the choice of k in the k-nearest neighbor graph, computational expense for large datasets, and the assumption that data lies on a single connected manifold. These limitations have motivated the development of more modern dimensionality reduction techniques like t-SNE and UMAP.
## Links

- [Multidimensional Scaling](https://en.wikipedia.org/wiki/Multidimensional_scaling) : Wikipedia page about Multidimensional Scaling, a technique used to project high-dimensional data into a lower-dimensional space while preserving pairwise distances.
- [Isomap](https://en.wikipedia.org/wiki/Isomap) : Wikipedia page about Isomap, a non-linear dimensionality reduction technique that preserves the local similarity structure of data by using geodesic distances.

## Topics

![[topics/Concept/Manifold Hypothesis]]

![[topics/Concept/Multidimensional Scaling MDS]]

![[topics/Concept/Isomap]]

![[topics/Concept/K Nearest Neighbor Graph]]