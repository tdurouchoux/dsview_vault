---
type: Concept
---

Gradient Highways refer to the direct pathways created by Attention Residuals for gradient flow during backpropagation. Unlike traditional residual connections, where gradients must traverse through multiple intermediate layers, Attention Residuals enable gradients to propagate directly from the loss to early layers via the alpha gates. This direct routing mechanism helps mitigate the vanishing gradient problem, leading to more efficient training and better gradient distribution across the network.