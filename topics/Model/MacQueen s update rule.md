---
type: Model
---

A mini-batch update rule for k-means introduced by J. MacQueen in 1967. It accumulates statistics (sum and count) for each cluster without discarding them, meaning centroids are updated based on the uniform mean of all points assigned to them since the start of training. This approach can lead to suboptimal performance due to outdated assignments, which e-means addresses with exponential moving average updates.