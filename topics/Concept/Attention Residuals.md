---
type: Concept
---

Attention Residuals is an architectural innovation in transformer models that replaces traditional fixed residual connections with a learned routing mechanism. Unlike standard residual connections, which pass information sequentially from one layer to the next, Attention Residuals allow each layer to dynamically query and blend outputs from all previous layers using a gating mechanism (alpha gate). This approach enables direct gradient flow across layers, mitigating the vanishing gradient problem and improving gradient propagation, especially in deep networks. The mechanism involves maintaining a 'history database' of all intermediate outputs, which layers can query and weight according to learned preferences, effectively creating a depth-wise memory system.