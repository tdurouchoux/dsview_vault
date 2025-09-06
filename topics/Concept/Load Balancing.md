---
type: Concept
---

Load balancing in the context of Mixture of Experts (MoE) models refers to the process of distributing the computational load evenly across the different experts in the model. This is important because, without load balancing, some experts might be overloaded with many input tokens, while others might be underutilized. Load balancing ensures that all experts receive a roughly equal number of training examples, which helps to prevent certain experts from becoming bottlenecks and improves the overall efficiency and performance of the model. Techniques for load balancing include using an auxiliary loss function to encourage uniform routing and setting an expert capacity to limit the number of tokens an expert can process.