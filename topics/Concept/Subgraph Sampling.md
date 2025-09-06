---
type: Concept
---

Subgraph sampling is a process used in GNN training where small, tractable subgraphs are sampled from a larger graph to create input examples. This process is crucial for scaling GNN training to large datasets. TF-GNN provides tooling for dynamic and interactive subgraph sampling, which can be configured at various scales, from interactive use in a Colab notebook to distributed sampling using Apache Beam for huge datasets.