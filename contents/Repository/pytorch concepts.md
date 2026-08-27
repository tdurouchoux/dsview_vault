---
already_read: true
link: https://github.com/pyc-team/pytorch_concepts
read_priority: 0
relevance: 4
source: null
tags:
- Deep_Learning
type: Content
upload_date: '2026-08-27'
---

https://github.com/pyc-team/pytorch_concepts

## Summary

PyC is an alpha-stage PyTorch/PyTorch Lightning library for building interpretable, causally transparent deep-learning models via concepts and probabilistic graphical models.

**Core idea**
- Library name reflects dual focus: concepts as building blocks and modeling P(y|C).

**Stack (modular, multi-level)**
- **No-code (Conceptarium)**: Hydra + WandB for config-driven large-scale experiments.
- **High-level**: 1-line model instantiation as PyTorch or PyTorch Lightning modules.
- **Mid-level**: define variables, connect via interpretable layers, run probabilistic inference.
- **Low-level**: interpretable layers, annotated tensors, interventions, metrics, losses, datasets.

**Status & practicalities**
- Alpha software, unstable public APIs.
- Install via `pip install --pre pytorch-concepts[data]` (or core-only).
- Documentation, user guide, and contributing guidelines available.

## Links

- [PyTorch Concepts PyPI Package](https://pypi.org/project/pytorch-concepts/) : The official PyPI page for the PyTorch Concepts library, providing installation instructions, version details, and package metadata.
- [PyTorch Concepts Documentation - Installation Guide](https://pytorch-concepts.readthedocs.io/en/latest/guides/installation.html) : Detailed installation instructions for the PyTorch Concepts library, including prerequisites, conda setup, and core vs. data dependencies.
- [PyTorch Concepts Documentation - User Guide](https://pytorch-concepts.readthedocs.io/en/latest/guides/using.html) : A user guide for building interpretable deep learning models using PyTorch Concepts, covering high-level APIs, mid-level probabilistic graphical models, and low-level interpretable layers.
- [PyTorch Concepts Documentation](https://pytorch-concepts.readthedocs.io/) : The official documentation hub for PyTorch Concepts, including API references, tutorials, and conceptual overviews of the library's modular software stack.


## Topics

![[topics/Library/PyC]]

![[topics/Library/PyTorch Lightning]]

![[topics/Library/Hydra]]

![[topics/Library/WandB]]

![[topics/Concept/Interpretable Deep Learning]]

![[topics/Concept/Probabilistic Graphical Models]]

![[topics/Concept/Concept based Modeling]]

![[topics/Library/PyTorch]]