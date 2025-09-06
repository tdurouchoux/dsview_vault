---
type: Concept
---

Expert Capacity in Mixture of Experts (MoE) models refers to the maximum number of tokens that an expert can process at a given time. It is a crucial concept for managing the computational load and ensuring efficient training and inference. By setting an expert capacity, we can prevent any single expert from being overwhelmed with too many tokens, which could lead to bottlenecks and inefficiencies. The expert capacity is determined by the capacity factor, which is a hyperparameter that can be adjusted to balance the trade-off between computational cost and model performance. A higher capacity factor allows for more tokens to be processed by each expert, but it also increases communication costs and memory requirements.