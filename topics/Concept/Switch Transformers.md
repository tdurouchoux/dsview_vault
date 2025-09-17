---
type: Concept
---

Switch Transformers are a type of transformer model that utilizes Mixture of Experts (MoE) layers, where each token is routed to a single expert based on a gating mechanism. This approach reduces router computation, batch size per expert, communication costs, and maintains model quality, making it more efficient for training and inference.