---
type: Concept
---

Momentum is an optimization technique used to accelerate gradient descent. It introduces a short-term memory by adding a fraction of the previous update vector to the current gradient. This helps in smoothing out updates, accelerating convergence in relevant directions, and dampening oscillations. The momentum term is controlled by a hyperparameter beta, which determines the contribution of the past gradient. Momentum can handle pathological curvature better than standard gradient descent and allows for larger step sizes without divergence.