---
already_read: true
link: https://github.com/dholzmueller/pytabkit
read_priority: 0
relevance: 5
source: null
tags:
- Deep_Learning
type: Content
upload_date: '2026-04-15'
---

https://github.com/dholzmueller/pytabkit
## Summary

PyTabKit is a Python library providing scikit-learn interfaces for modern tabular data classification and regression models, benchmarked in a NeurIPS 2024 paper. Key features include:

- **Models**: Supports RealMLP (neural nets with tuned defaults/HPO/ensembling), XGBoost/LightGBM/CatBoost (gradient-boosted trees), MLP/ResNet/FTT, TabR, TabM, and xRFM. Includes post-hoc calibration and refinement stopping.
- **Benchmarking**: Includes code for dataset download, parallel execution, and result analysis (recommended: TabArena for method evaluation).
- **Preprocessing**: Handles missing values, categorical features, and robust scaling.
- **Installation**: Optional dependencies via `pip install pytabkit[models]`; GPU support for some models.
- **Usage**: Simple scikit-learn-style API (e.g., `RealMLP_TD_Classifier`). Supports cross-validation, ensembling, and hyperparameter optimization.
- **Key Recommendations**:
  - For best results: Use `Ensemble_HPO_Classifier` with full Caruana ensembling or `RealMLP_HPO_Classifier`.
  - AutoGluon is an alternative for top performance (includes RealMLP/TabM).
- **Citation**: Holzmüller et al., "Better by default: Strong pre-tuned MLPs and boosted trees on tabular data" (NeurIPS 2024).
## Links

- [NeurIPS 2024 Paper: Better by Default - Strong Pre-Tuned MLPs and Boosted Trees on Tabular Data](https://arxiv.org/abs/2407.04491) : This link points to the arXiv paper titled 'Better by Default: Strong Pre-Tuned MLPs and Boosted Trees on Tabular Data,' which is the foundational research work behind the PyTabKit library. It provides theoretical and empirical insights into the models and benchmarks included in PyTabKit.
- [RealMLP-TD-S Standalone Implementation](https://github.com/dholzmueller/realmlp-td-s_standalone) : This link leads to the standalone implementation of the RealMLP-TD-S model, a key component of PyTabKit. It is useful for understanding the implementation details and experimenting with the model independently of the full PyTabKit library.
- [Grinsztajn et al. Benchmark Code](https://github.com/LeoGrin/tabular-benchmark/tree/better_by_default) : This link directs to the benchmark code used by Grinsztajn et al., which is integrated into PyTabKit. It is essential for reproducing the benchmarks and understanding the evaluation framework for tabular data models.
- [PyTabKit Documentation](https://pytabkit.readthedocs.io/en/latest/) : This link provides access to the official documentation for PyTabKit, including detailed explanations of its features, models, and benchmarking tools. It is a critical resource for users looking to understand how to implement and utilize PyTabKit effectively.
- [TabArena Benchmark Platform](https://tabarena.ai) : This link leads to TabArena, the benchmarking platform referenced in PyTabKit. It is designed for evaluating tabular data models and is recommended for method evaluation in the PyTabKit ecosystem. The platform provides a standardized environment for comparing model performance.

## Topics

![[topics/Model/TabM]]

![[topics/Model/TabR]]

![[topics/Concept/Tabular Data Benchmarking]]

![[topics/Concept/Calibration]]

![[topics/Library/pytabkit]]

![[topics/Model/RealMLP]]

![[topics/Concept/Hyperparameter Optimization HPO]]

![[topics/Concept/Ensemble Learning]]