---
already_read: false
link: https://blog.tensorflow.org/2024/02/graph-neural-networks-in-tensorflow.html
read_priority: 3
relevance: 0
source: null
tags:
- Graph
- Deep_Learning
type: Content
upload_date: '2025-05-03'
---

https://blog.tensorflow.org/2024/02/graph-neural-networks-in-tensorflow.html
## Summary

The article introduces TensorFlow GNN 1.0 (TF-GNN), a library for building graph neural networks (GNNs) at scale. GNNs leverage both graph connectivity and node/edge features to make predictions about graphs, nodes, or edges. TF-GNN supports heterogeneous graphs, where types and relations are represented by distinct sets of nodes and edges.

Key features of TF-GNN include:

1. **Graph Representation**: Graphs are represented using `tfgnn.GraphTensor`, a composite tensor type that stores both graph structure and features.
2. **Subgraph Sampling**: TF-GNN provides tools for dynamic and interactive subgraph sampling, which is crucial for GNN training. It supports sampling at various scales, from interactive notebooks to distributed systems using Apache Beam.
3. **Message-Passing Neural Networks**: TF-GNN supports message-passing neural networks, where nodes receive messages from their neighbors and update their hidden states. This process aggregates information from the node's neighborhood.
4. **Model Building**: The library supports building GNN architectures at various levels of abstraction, from predefined Keras layers to custom models using primitives for passing data around the graph.
5. **Training Orchestration**: TF-GNN includes a Runner for orchestrating the training of Keras models, supporting distributed training, multi-task learning, and model attribution using integrated gradients.

The article concludes by encouraging users to try the Colab demo, browse user guides, and read the paper for more details. The development of TF-GNN 1.0 involved collaboration between Google Research, Google Core ML, and Google DeepMind.
## Links

- [TensorFlow Guide to Keras](https://www.tensorflow.org/guide/keras) : Official TensorFlow guide to Keras, a high-level API for building and training deep learning models.
- [Introduction to Graph Neural Networks](https://distill.pub/2021/gnn-intro/) : A comprehensive introduction to Graph Neural Networks (GNNs), explaining their principles and applications.
- [Node2Vec](https://snap.stanford.edu/node2vec/) : Node2Vec is an algorithm for learning continuous feature representations for nodes in graphs.
- [In-Memory Sampler Guide](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/guide/inmemory_sampler.md) : Guide on using the in-memory sampler for graph neural networks in TensorFlow GNN.
- [Apache Beam](https://beam.apache.org/) : Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines.

## Topics

![[topics/Model/Graph Neural Networks)]]

![[topics/Model/Message Passing Neural Networks MPNNs)]]

![[topics/Library/TensorFlow GNN)]]

![[topics/Concept/Unsupervised Learning in GNNs)]]

![[topics/Concept/Subgraph Sampling)]]