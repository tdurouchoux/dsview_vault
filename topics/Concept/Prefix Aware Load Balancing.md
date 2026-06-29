---
type: Concept
---

Prefix-aware load balancing is a strategy used to distribute incoming requests across multiple replicas of a model in a way that optimizes resource utilization and performance. It takes into account the state of the model's KV (key-value) cache, ensuring that requests are routed to replicas with the most efficient cache state, thereby improving throughput and reducing latency.