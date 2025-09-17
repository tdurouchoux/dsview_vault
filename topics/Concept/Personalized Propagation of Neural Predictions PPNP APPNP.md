---
type: Concept
---

PPNP (Personalized Propagation of Neural Predictions) and APPNP (Approximate Personalized Propagation of Neural Predictions) are algorithms designed for representation learning and node classification in attributed homogeneous graphs. These algorithms first train a multilayer neural network using node attributes as input and then diffuse the predictions across the graph using a method based on Personalized PageRank. This approach makes PPNP and APPNP fast and scalable, particularly in semi-supervised settings where only a small number of nodes have labels.