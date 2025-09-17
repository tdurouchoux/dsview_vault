---
type: Concept
---

A feature store is a component of a feature platform designed to reduce feature retrieval latency and store computed features for reuse, reducing computation costs. It can be a key-value store that stores computed features in-memory and may also handle persisting feature values on disk to ensure train-predict consistency. Common key-value stores include DynamoDB, Redis, and Bigtable.