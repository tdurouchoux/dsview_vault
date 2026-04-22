---
already_read: true
link: https://github.com/TutteInstitute/evoc
read_priority: 0
relevance: 5
source: Marino
tags:
- Unsupervised_Learning
type: Content
upload_date: '2026-04-22'
---

https://github.com/TutteInstitute/evoc
## Summary

EVōC (Embedding Vector Oriented Clustering) is a Python library for fast and flexible clustering of high-dimensional embedding vectors (e.g., from CLIP, sentence-transformers, OpenAI, or Cohere). Key features include:

- **Performance**: Optimized for CPU, with faster clustering than UMAP + HDBSCAN combinations.
- **Multi-granularity**: Generates hierarchical clusters and automatically selects the number of clusters.
- **Quantization support**: Works out-of-the-box with int8 or binary quantized embeddings.
- **Scikit-learn API**: Familiar interface for integration with existing workflows.

**Usage**:
```python
import evoc
from sklearn.datasets import make_blobs

data, _ = make_blobs(n_samples=100_000, n_features=1024, centers=100)
clusterer = evoc.EVoC()
cluster_labels = clusterer.fit_predict(data)
cluster_layers = clusterer.cluster_layers_  # Multi-level granularity
hierarchy = clusterer.cluster_tree_         # Cluster hierarchy
duplicates = clusterer.duplicates_          # Near-duplicate detection
```

**Dependencies**: `numpy`, `scikit-learn`, `numba`, `tqdm`, `tbb`.
**Installation**: `pip install evoc` or from source (`git+https://github.com/TutteInstitute/evoc.git`).

**Citation**: Based on the PLSCAN algorithm (arXiv:2512.16558). License: BSD-2-Clause. Early beta; feedback welcome.
## Links

- [EVōC Documentation on Read the Docs](https://evoc.readthedocs.io/en/latest/) : This link points to the full documentation of the EVōC library, providing detailed guides, API references, and usage examples for embedding vector clustering.
- [PLSCAN Paper on arXiv](https://arxiv.org/abs/2512.16558) : This link leads to the arXiv paper titled 'Persistent Multiscale Density-based Clustering,' which is the foundational research paper for the clustering algorithm implemented in EVōC. This paper provides theoretical insights into the clustering methodology used in EVōC.

## Topics

![[topics/Library/evoc]]

![[topics/Concept/Multi granularity clustering]]

![[topics/Concept/Fuzzy Deduplication]]

![[topics/Concept/Hierarchical Clustering]]

![[topics/Model/PLSCAN]]

![[topics/Concept/Quantization]]