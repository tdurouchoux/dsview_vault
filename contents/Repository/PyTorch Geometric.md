---
already_read: true
link: https://github.com/pyg-team/pytorch_geometric
read_priority: 0
relevance: 5
source: null
tags:
- Graph
type: Content
upload_date: '2026-08-27'
---

https://github.com/pyg-team/pytorch_geometric

## Summary

PyTorch Geometric (PyG) is a PyTorch-based library for building and training Graph Neural Networks (GNNs) on structured data, offering a unified API, scalability, and a rich ecosystem of models, layers, and utilities.

- **Core purpose**: Enables geometric deep learning on graphs, point clouds, and 3D meshes
- **Key features**: PyTorch-native design, `torch.compile` support, multi-GPU training, and efficient sparse tensor operations

**Library Highlights**
- Easy-to-use API with 10-20 lines for basic GNN training
- Comprehensive collection of state-of-the-art GNN architectures (GCN, GAT, GraphSAGE, etc.)
- Flexible message-passing interface for custom GNN development
- Scalable solutions for large graphs (NeighborLoader, ClusterGCN, GraphSAINT)
- Support for heterogeneous graphs, dynamic graphs, and 3D data

**Architecture**
- **Engine**: PyTorch backend with `torch.compile` and TorchScript support
- **Storage**: Handles large-scale graph data, sampling, and heterogeneous graphs
- **Operators**: Message passing, pooling, normalization, and utility functions
- **Models**: Pre-built GNNs (SchNet, DimeNet, Node2Vec, etc.) and customizable templates

**Implemented Components**
- **GNN Layers**: GCNConv, GATConv, GraphConv, SAGEConv, TransformerConv, etc.
- **Pooling Layers**: Top-K, DiffPool, SAGPooling, MinCut, ASAPooling, etc.
- **GNN Models**: DeepGCN, GNNExplainer, GraphUNet, TGN, etc.
- **Utilities**: DropEdge, GraphNorm, GDC, LabelPropagation, etc.
- **Scalable GNNs**: NeighborLoader, ClusterGCN, GraphSAINT, ShaDow, SIGN

**Installation**
- Base install: `pip install torch_geometric`
- Full features require optional libraries: `pyg-lib`, `torch-scatter`, `torch-sparse`
- Pre-built wheels available for PyTorch 1.4+ and CUDA variants
- ROCm support via community repository

## Links

- [PyTorch Geometric Documentation](https://pytorch-geometric.readthedocs.io) : Comprehensive documentation for PyTorch Geometric, including tutorials, API references, and guides for using the library.
- [PyG 1.0 Paper (ICLR 2019)](https://arxiv.org/abs/1903.02428) : Research paper introducing PyTorch Geometric (PyG) version 1.0, covering its design principles and applications in geometric deep learning.
- [PyG 2.0 Paper (Temporal Graph Learning Workshop @ KDD 2025)](https://www.arxiv.org/abs/2507.16991) : Research paper introducing PyTorch Geometric (PyG) version 2.0, highlighting advancements in scalability and real-world graph applications.
- [PyG Colab Notebooks](https://pytorch-geometric.readthedocs.io/en/latest/get_started/colabs.html) : Interactive Colab notebooks demonstrating how to use PyTorch Geometric for various graph-based deep learning tasks.
- [PyG External Resources](https://pytorch-geometric.readthedocs.io/en/latest/external/resources.html) : Curated list of external resources, including research papers, tutorials, and community projects related to PyTorch Geometric.


## Topics

![[topics/Library/PyTorch Geometric]]

![[topics/Model/Graph Neural Network]]

![[topics/Model/GCNConv]]

![[topics/Model/Graph Attention Network GAT]]

![[topics/Dataset/Cora]]

![[topics/Tool/torch compile]]

![[topics/Tool/DataPipe]]

![[topics/Concept/Geometric Deep Learning]]

![[topics/Concept/Message Passing]]