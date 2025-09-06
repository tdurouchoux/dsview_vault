---
type: Concept
---

Layer normalization is a technique used to normalize the inputs of each layer in a neural network. It helps stabilize and accelerate the training process by maintaining the mean and variance of the layer inputs. In Transformers, layer normalization is applied after each sub-layer, including the self-attention mechanism and the feed-forward network, to ensure that the inputs to each layer have similar distributions.