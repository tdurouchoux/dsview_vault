---
type: Concept
---

Load balancing in Mixture of Experts (MoE) models involves distributing tokens evenly across experts to prevent overloading specific experts, which can lead to inefficient training. Techniques such as auxiliary loss functions and expert capacity thresholds are used to ensure that all experts receive a roughly equal number of training examples, promoting balanced and efficient training.