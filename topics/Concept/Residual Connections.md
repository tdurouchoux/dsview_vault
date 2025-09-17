---
type: Concept
---

Residual connections, also known as skip connections, are a technique used in deep neural networks to help mitigate the vanishing gradient problem. They involve adding the input of a layer to its output before passing it to the next layer. This allows gradients to flow more easily through the network during backpropagation, enabling the training of very deep networks. In the context of Transformers, residual connections are applied around both the self-attention sub-layer and the feed-forward network sub-layer within each encoder and decoder block.