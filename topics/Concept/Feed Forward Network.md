---
type: Concept
---

A feed-forward network (FFN) is a fully connected network that applies successive linear transformations interspersed with non-linear activation functions. In the context of Transformers, FFNs are used in each encoder and decoder block to introduce non-linearity and complexity to the model. The FFN typically consists of two linear transformations with a ReLU activation in between. This structure allows the model to learn more complex patterns and transformations that pure attention mechanisms alone cannot capture.