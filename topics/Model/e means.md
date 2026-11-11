---
type: Model
---

A modern optimization algorithm for the k-means clustering problem, designed to replace Lloyd's algorithm. e-means uses mini-batch updates with exponential moving averages (EMA) to achieve faster convergence and lower loss. It incorporates automatic hyperparameter tuning via scaling laws, novel initialization and finalization methods, cosine-scheduled decay rates, and a dead-cluster revival strategy. The algorithm is highly parallelizable and includes specialized GPU kernels for wall-clock speedups.