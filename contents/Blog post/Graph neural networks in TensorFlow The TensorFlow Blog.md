---
already_read: false
link: https://blog.tensorflow.org/2024/02/graph-neural-networks-in-tensorflow.html
read_priority: 3
relevance: 0
source: null
tags:
- Graph
- Supervised_Learning
type: Content
upload_date: '2025-05-03'
---

https://blog.tensorflow.org/2024/02/graph-neural-networks-in-tensorflow.html
## Summary

The TensorFlow blog post introduces TensorFlow GNN 1.0 (TF-GNN), a library for building graph neural networks (GNNs) at scale. GNNs leverage both graph connectivity and node/edge features to make predictions about graphs, nodes, or edges. TF-GNN supports heterogeneous graphs with distinct node and edge types, represented as `GraphTensor` objects in TensorFlow. Key features include dynamic subgraph sampling for efficient training, message-passing neural networks for aggregating node information, and support for both supervised and unsupervised training. The library offers various levels of abstraction for building GNN architectures, from predefined Keras models to custom implementations using primitives. The TF-GNN Runner provides tools for training orchestration, including distributed training and multi-task learning. The post concludes with a call to explore the library through demos, user guides, and a research paper.
## Links

- [TensorFlow GNN 1.0 User Guide for Beam-Based Sampling](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/guide/beam_sampler.md) : User guide for TensorFlow GNN 1.0, focusing on beam-based sampling techniques for graph neural networks.
- [TensorFlow GNN 1.0 User Guide for GNN Modeling](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/guide/gnn_modeling.md) : User guide for TensorFlow GNN 1.0, focusing on modeling techniques for graph neural networks.
- [TensorFlow GNN 1.0 User Guide for Runner](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/guide/runner.md) : User guide for TensorFlow GNN 1.0, focusing on the runner component for orchestrating training tasks.
- [TensorFlow GNN 1.0 User Guide for In-Memory Sampling](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/guide/inmemory_sampler.md) : User guide for TensorFlow GNN 1.0, focusing on in-memory sampling techniques for graph neural networks.

## Topics

![](topics/Library/TensorFlow%20GNN)

![](topics/Model/Graph%20Neural%20Networks)

![](topics/Concept/GraphTensor)

![](topics/Concept/Subgraph%20Sampling)

![](topics/Concept/Message%20Passing%20Neural%20Networks)

![](topics/Concept/Unsupervised%20Learning%20with%20GNNs)