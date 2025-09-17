---
type: Concept
---

Label smoothing is a regularization technique used to prevent neural networks from becoming overconfident in their predictions. Instead of using one-hot encoded labels, label smoothing assigns a small probability to all classes, including the incorrect ones. This helps the model generalize better by reducing the impact of noisy or incorrect labels and encouraging it to distribute its confidence more evenly across the classes. In the context of Transformers, label smoothing is often applied during training to improve the model's robustness.