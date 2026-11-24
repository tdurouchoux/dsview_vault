---
already_read: false
link: https://github.com/inseefrlab/torchTextClassifiers
read_priority: 5
relevance: 0
source: null
tags:
- Natural_Language_Processing
- Python
- Deep_Learning
type: Content
upload_date: '2026-11-24'
---

https://github.com/inseefrlab/torchTextClassifiers

## Summary

torchTextClassifiers is a PyTorch-based framework for text classification with categorical variables, offering modularity, explainability, and seamless integration with PyTorch Lightning.

**Core Features**
- Handles text + categorical variables without manual encoding via `ValueEncoder`.
- Supports HuggingFace tokenizers and fastText’s ngram tokenizer.
- Modular design: `TokenEmbedder` (token → vectors) + `SentenceEmbedder` (aggregation) + `CategoricalVariableNet` + `ClassificationHead`.
- Two usage paths: prebuilt `TextClassificationModel` (via `ModelConfig`) or custom `nn.Module` (via `from_model()`).
- Includes reference architectures (e.g., `MultiLevelTextClassificationModel` for multi-task classification).

**Task Support**
- Multiclass and multilabel classification.

**Training & Usability**
- PyTorch Lightning integration for automated training (callbacks, early stopping, logging).
- Minimal-code API for training, evaluation, and prediction.

**Explainability**
- Captum integration for gradient-based token attribution (`explain_with_captum=True`).
- Label attention for class-specific token explanations (`explain_with_label_attention=True`, configurable via `n_heads_label_attention`).

**Resources**
- Documentation: https://inseefrlab.github.io/torchTextClassifiers/
- Examples: basic/multi-class classification, mixed features, multi-level classification.
- MIT License.

## Links

- [PyTorch Official Documentation](https://pytorch.org/) : The official documentation and resources for PyTorch, a popular open-source machine learning library used for building and training neural networks. This is the foundational framework upon which torchTextClassifiers is built.
- [PyTorch Lightning Documentation](https://lightning.ai/docs/pytorch/stable/) : The official documentation for PyTorch Lightning, a lightweight PyTorch wrapper that simplifies training and scaling of deep learning models. This framework is used in torchTextClassifiers for automated training, callbacks, early stopping, and logging.


## Topics

![[topics/Library/torchTextClassifiers]]

![[topics/Library/Captum]]

![[topics/Library/HuggingFace tokenizers]]

![[topics/Concept/Label attention]]

![[topics/Concept/Multiclass and multilabel classification]]

![[topics/Library/PyTorch Lightning]]