---
type: Concept
---

A simple neural network applied to each position in the sequence independently and identically. It consists of two linear transformations with a non-linear activation function applied in between. The feed-forward network (FFN) is a fully connected network that processes the information captured by the attention mechanism, applying non-linear transformations to detect deeper and more abstract features in the data. In the context of Transformers, FFNs are used in each encoder and decoder block to introduce non-linearity and complexity to the model. This structure allows the model to learn more complex patterns and transformations that pure attention mechanisms alone cannot capture.