---
type: Concept
---

GraphSAGE is a flexible, inductive framework for generating node embeddings using graph convolutional networks. Unlike traditional methods that require the entire graph for training, GraphSAGE generates embeddings by sampling and aggregating information from a node's local neighborhood. This makes it scalable to large graphs and suitable for both supervised and unsupervised learning tasks, including node classification, link prediction, and representation learning. GraphSAGE supports various aggregation methods such as mean, maxpool, meanpool, and attentional aggregators, making it versatile for different types of graph data.