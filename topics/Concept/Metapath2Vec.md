---
type: Concept
---

Metapath2Vec is an algorithm for unsupervised, metapath-guided representation learning in heterogeneous networks. It generates node embeddings by performing random walks guided by metapaths, which are predefined sequences of node types, and then applying the word2vec algorithm from Gensim. Metapath2Vec takes into account the network structure while ignoring node attributes, making it useful for tasks where the graph topology and node types are the primary sources of information. The learned node representations can be used in downstream machine learning models for tasks such as node classification and link prediction.