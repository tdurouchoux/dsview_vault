---
type: Concept
---

A technique used in optimization where centroids are updated using a weighted average of past and current batch statistics. In e-means, EMA updates allow centroids to track recent assignments while forgetting older ones, improving convergence speed and reducing the likelihood of getting stuck in local minima. This approach is contrasted with gradient descent updates, which may overshoot the convex hull of assigned points.