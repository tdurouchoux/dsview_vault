---
type: Concept
---

Residual connections, also known as skip connections, are connections that skip one or more layers and directly connect earlier layers to deeper layers in the network. They are used to mitigate the vanishing gradient problem and help in training very deep networks by allowing gradients to flow more easily through the network. In Transformers, residual connections are used around each sub-layer, followed by layer normalization.