---
type: Model
---

A Graph Attention Network (GAT) is a type of graph neural network that uses attention mechanisms to dynamically compute the importance of neighboring nodes during message passing. Unlike traditional GNNs with fixed aggregation functions, GATs assign attention weights to edges based on a scoring function measuring relevance to the central node, enabling the model to focus on the most relevant nodes. GATs are permutation-invariant and support both sparse and dense adjacency matrices, making them effective for tasks such as node classification, link prediction, representation learning, and graph-level predictions in heterogeneous, homogeneous, or dynamic graphs. Implemented in libraries like StellarGraph.