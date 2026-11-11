---
already_read: true
link: https://e-means.github.io/
read_priority: 0
relevance: 4
source: linkedin
tags:
- Unsupervised_Learning
type: Content
upload_date: '2026-11-11'
---

https://e-means.github.io/

## Summary

e-means is a modern k-means replacement that achieves ~10× speedup in epochs and wall-clock time while improving loss.

**Core improvement**
- 10–45× faster on GPU vs. Flash-KMeans, 8–15× on CPU vs. Faiss, at equal or better loss.
- Reaches Lloyd’s 25-epoch loss in 1.2–3 epochs (1.6–2.4 on VIBE benchmarks).

**Algorithm**
- Mini-batch updates with exponential moving averages (EMA) for centroids.
- Automatically sets batch size and step size via scaling laws (no hyperparameter tuning).
- Cosine-scheduled decay rate for step size α (from α₀ to 0.1α₀).
- Finalization stage refines centroids to exact last-epoch means.

**Key components**
- EMA updates outperform gradient descent (stable, centroids stay in convex hull).
- Dead-cluster revival by splitting large clusters (reduces dead clusters from ~2k to <50 in tests).
- Specialized GPU kernels fuse nearest-centroid assignment for wall-clock gains.

**Validation**
- Tested on 24 datasets (100k–100M points), consistently outperforms Lloyd.
- Better escapes local minima (e.g., 46% → 0% stuck cases in 5-blob toy example).

**Usage**
- Available in Faiss: `faiss.contrib.e_means.Emeans`.
- Paper: [arXiv:2611.09501](https://arxiv.org/abs/2611.09501).

## Links

- [e-means Paper on arXiv](https://arxiv.org/abs/2611.09501) : The official arXiv paper introducing e-means, a modern k-means algorithm developed at Meta FAIR. It details the methodology, experimental results, and theoretical foundations of e-means, including its 10x speedup over traditional Lloyd's algorithm while achieving lower loss.
- [e-means Implementation in FAISS](https://github.com/facebookresearch/faiss/tree/main/contrib/e_means) : The GitHub repository for the e-means implementation within the FAISS library. This includes the codebase for e-means, enabling users to integrate the algorithm into their projects for efficient k-means clustering.


## Topics

![[topics/Model/e means]]

![[topics/Model/Lloyd s algorithm]]

![[topics/Model/MacQueen s update rule]]

![[topics/Model/Flash KMeans]]

![[topics/Concept/Exponential Moving Average EMA updates]]

![[topics/Concept/Dead cluster revival]]

![[topics/Tool/FAISS]]

![[topics/Concept/Scaling Laws]]