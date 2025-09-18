---
already_read: false
link: https://distill.pub/2021/gnn-intro/
read_priority: 1
relevance: 0
source: null
tags:
- Graph
- Deep_Learning
type: Content
upload_date: '2024-04-24'
---

https://distill.pub/2021/gnn-intro/
## Summary

The article provides an introduction to Graph Neural Networks (GNNs), which are neural networks designed to operate on graph-structured data. The content is divided into several sections, each focusing on different aspects of GNNs.

The article begins by explaining what graphs are and how they can represent various types of data, such as images, text, molecules, social networks, and citation networks. It then discusses the challenges of using graphs in machine learning, including the need for permutation-invariant operations and efficient representations of sparse matrices.

The core of the article is dedicated to building and understanding GNNs. It starts with the simplest GNN architecture, which updates node, edge, and global representations using separate multilayer perceptrons (MLPs). The article then introduces the concept of pooling, which allows information to be gathered and aggregated from different parts of the graph for making predictions. This is followed by the introduction of message passing, where neighboring nodes or edges exchange information to influence each other's updated embeddings.

The article also covers more advanced topics, such as learning edge representations, adding global representations, and using attention mechanisms in GNNs. It provides a playground for readers to experiment with different GNN architectures and understand their impact on a real-world task.

The article concludes with a discussion on the design choices and empirical lessons learned from exploring the architecture space of GNNs. It highlights the importance of inductive biases, the challenges of sampling and batching in GNNs, and the potential of GNNs in generative modeling and graph explanations.

Overall, the article serves as a comprehensive guide to understanding and building modern GNNs, with a focus on the design choices and practical considerations involved in their implementation.
## Links

- [Understanding Convolutions on Graphs](https://doi.org/10.23915/distill.00032) : This link points to an article that explains convolutions on graphs, which is a fundamental concept in graph neural networks. It provides insights into how convolutions over images generalize naturally to convolutions over graphs.
- [GitHub Repository for the Article](https://github.com/distillpub/post--gnn-intro) : This link points to the GitHub repository for the article. It contains the source code, diagrams, and additional resources related to the article on graph neural networks.

## Topics

![[topics/Concept/Graphs)]]

![[topics/Concept/Message Passing)]]

![[topics/Concept/Pooling)]]

![[topics/Model/Graph Neural Networks)]]

![[topics/Concept/Graph Attention Network GAT)]]