---
type: Concept
---

A strategy in e-means to address the issue of 'dead' clusters, which are centroids that end up with no assigned points during optimization. Instead of reinitializing dead clusters randomly, e-means revives them by splitting large, active clusters into two. This approach preserves the codebook capacity and improves clustering quality, particularly for large codebooks.