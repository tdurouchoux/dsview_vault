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

The article provides an introduction to Graph Neural Networks (GNNs), which are neural networks adapted to leverage the structure and properties of graphs. The content is divided into four main parts:

1. **Graph Data and Examples**: The article begins by explaining what graphs are and how they can represent various types of data, such as images, text, molecules, social networks, and citation networks. It also discusses different types of graph attributes and the structure of real-world graphs.

2. **Graph Prediction Tasks**: The article outlines three general types of prediction tasks on graphs: graph-level, node-level, and edge-level tasks. It provides examples of each type of task and explains how GNNs can be used to solve them.

3. **Challenges of Using Graphs in Machine Learning**: The article discusses the challenges of representing graphs in a format compatible with neural networks. It explains the problems with using adjacency matrices and introduces adjacency lists as a more efficient representation.

4. **Graph Neural Networks (GNNs)**: The article describes the components of GNNs, including the simplest GNN architecture and how it can be used to make predictions. It also discusses more sophisticated GNN models, such as those that use message passing and global representations. The article includes a GNN playground where readers can experiment with different model architectures and see how they affect the model's performance.

The article also provides a summary of empirical GNN design lessons, discussing the performance of different GNN architectures and design choices. It concludes with a discussion of other types of graphs, sampling graphs and batching in GNNs, inductive biases, comparing aggregation operations, GCN as subgraph function approximators, the graph dual, graph convolutions as matrix multiplications, graph attention networks, graph explanations and attributions, and generative modeling.

The article is written by Benjamin Sanchez-Lengeling, Emily Reif, Adam Pearce, and Alexander B. Wiltschko, all from Google Research. It was published on September 2, 2021, and is licensed under Creative Commons Attribution CC-BY 4.0. The diagrams and text are available on GitHub, and the figures that have been reused from other sources do not fall under this license.
## Links

- [Understanding Convolutions on Graphs](https://doi.org/10.23915/distill.00032) : This link points to an article that explains convolutions on graphs, which is a fundamental concept in graph neural networks. It provides insights into how convolutions, typically used in image processing, can be adapted for graph-structured data.
- [GitHub Repository for the Article](https://github.com/distillpub/post--gnn-intro) : This link points to the GitHub repository of the article. It contains the source code, diagrams, and additional resources related to the article. It is useful for those who want to explore the technical details or contribute to the project.

## Topics

![](topics/Concept/Graph%20Theory)

![](topics/Concept/Pooling)

![](topics/Concept/Graph%20Attention%20Networks)

![](topics/Concept/Graph%20Explanations)

![](topics/Model/Graph%20Neural%20Networks)

![](topics/Concept/Message%20Passing)