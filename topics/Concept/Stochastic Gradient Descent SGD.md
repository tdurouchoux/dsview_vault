---
date: '2024-10-16'
type: Concept
---

Stochastic Gradient Descent (SGD) is an iterative optimization algorithm used in training machine learning models, particularly neural networks. Instead of calculating gradients from the entire training dataset to update model parameters, SGD updates parameters using a subset (or a single point) of the training data. This typically leads to faster convergence since the algorithm can start making progress on the learning task before processing the complete dataset. Variations include mini-batch SGD, where updates are made based on a small batch of data points.