---
type: Concept
---

The Alpha Gate is a learned routing mechanism introduced in Attention Residuals. It computes softmax-normalized weights (alpha weights) that determine how much of each past layer's output should be included as input to the current layer. The process involves four steps: (1) RMS normalization of the history tensor, (2) scoring via dot-product with a learned query vector, (3) softmax normalization of scores to produce alpha weights, and (4) blending the raw history using these weights. This mechanism enables dynamic and learned routing of information across layers, improving gradient flow and model performance.