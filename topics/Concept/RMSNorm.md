---
type: Concept
---

RMSNorm (Root Mean Square Layer Normalization) is a normalization technique used in transformer-based models as an alternative to Layer Normalization. RMSNorm scales the layer activations by dividing them by the root mean square, without enforcing zero mean or unit variance. This makes RMSNorm computationally cheaper than LayerNorm, as it avoids the need for mean and variance computations, reducing communication overhead on GPUs and improving training efficiency. RMSNorm has become a common choice in large-scale LLMs due to its efficiency and effectiveness in stabilizing activation scales.