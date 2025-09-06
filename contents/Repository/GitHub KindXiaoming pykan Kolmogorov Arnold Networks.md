---
already_read: false
link: https://github.com/KindXiaoming/pykan
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
type: Content
upload_date: '2024-06-12'
---

https://github.com/KindXiaoming/pykan
## Summary

Kolmogorov-Arnold Networks (KANs) are an alternative to Multi-Layer Perceptrons (MLPs) with strong mathematical foundations based on the Kolmogorov-Arnold representation theorem. Unlike MLPs, KANs have activation functions on edges rather than nodes, which can improve model accuracy and interpretability.

**Key Points:**
- **Installation:** Pykan can be installed via PyPI or GitHub, with Python 3.9.7 or higher and pip as prerequisites.
- **Efficiency Mode:** For better performance, use `model.speed()` before training to disable the symbolic branch.
- **Computation Requirements:** Examples can run on a single CPU, but larger tasks may require GPUs.
- **Tutorials and Documentation:** Quickstart with `hellokan.ipynb` and explore more tutorials for demos and hyperparameter tuning advice.
- **Hyperparameter Tuning:** Start with a simple setup, then gradually increase complexity. Focus on grid size and width, and consider sparsifying the network for interpretability.
- **Citation:** The paper "KAN: Kolmogorov-Arnold Networks" by Liu et al. (2024) is available on arXiv.
- **Contact:** For questions, contact zmliu@mit.edu.

**Author's Note:** KANs are designed for scientific applications and may require tuning for machine learning tasks. The author welcomes criticism and collaboration, especially for scientific discoveries and computing.
## Links

- [Pykan Documentation](https://kindxiaoming.github.io/pykan/) : The official documentation for Pykan, providing detailed information on how to use the library, including installation, usage examples, and API references.
- [KAN Paper](https://arxiv.org/abs/2404.19756) : The research paper titled 'KAN: Kolmogorov-Arnold Networks' which introduces the theoretical foundations and applications of KANs.
- [GraphKAN](https://github.com/WillHua127/GraphKAN-Graph-Kolmogorov-Arnold-Networks) : A GitHub repository for GraphKAN, an extension of KANs for graph-structured data.
- [KANRL](https://github.com/riiswa/kanrl) : A GitHub repository for KANRL, an implementation of KANs for reinforcement learning tasks.
- [EfficientKAN](https://github.com/Blealtan/efficient-kan) : A GitHub repository for EfficientKAN, an optimized implementation of KANs aimed at improving efficiency.

## Topics

![](topics/Model/Kolmogorov%20Arnold%20Networks%20KANs)