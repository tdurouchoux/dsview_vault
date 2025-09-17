---
type: Concept
---

Layer normalization is a technique used to normalize the inputs of each layer in a neural network. It helps stabilize and accelerate the training process by maintaining the mean and variance of the layer inputs. Unlike batch normalization, which normalizes across the batch dimension, layer normalization normalizes across the features for each individual example. This makes it particularly suitable for sequences of varying lengths and for models like Transformers that process sequences in parallel.