---
date: '2024-10-16'
type: Concept
---

Dropout is a regularization technique used in neural networks to prevent overfitting. During training, it randomly ignores a subset of neurons (along with their connections) with a specified probability before the forward pass, which forces the network to create multiple pathways and helps it learn to generalize better. At test time, all neurons are utilized, and their outputs may be scaled based on the dropout rate during training. This technique is particularly useful in dense layers of a neural network.