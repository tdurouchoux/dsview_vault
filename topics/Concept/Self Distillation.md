---
type: Concept
---

Self-distillation is a technique where a model improves itself by learning from its own outputs. Unlike traditional distillation, which relies on a stronger teacher model, self-distillation uses the model's own predictions as targets for fine-tuning. This approach can enhance performance without requiring external labeled data, verifiers, or reward models. In the context of code generation, self-distillation reshapes the model's token distributions to suppress distractor tails in precision-bound contexts (e.g., 'locks') while preserving useful diversity in exploration-bound contexts (e.g., 'forks').