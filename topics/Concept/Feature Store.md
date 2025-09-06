---
type: Concept
---

A feature store is a component of a feature platform that focuses on reducing feature retrieval latency and storing computed features for reuse. It acts as a key-value store that keeps computed features in-memory, allowing multiple models to access the same features without redundant computations. Feature stores can also handle persisting feature values on disk to ensure train-predict consistency. Common examples include DynamoDB, Redis, and Bigtable.