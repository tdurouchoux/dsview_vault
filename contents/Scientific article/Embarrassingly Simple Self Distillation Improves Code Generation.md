---
already_read: false
link: https://arxiv.org/pdf/2604.01193
read_priority: 5
relevance: 0
source: marimo
tags:
- Large_Language_Model
type: Content
upload_date: '2026-04-27'
---

https://arxiv.org/pdf/2604.01193
## Summary

Simple self-distillation (SSD) improves code generation by training a model on its own raw outputs. Key points:

- **Method**: Sample solutions from the base model with specific temperature and truncation settings, then fine-tune on those samples using standard supervised fine-tuning. No verifier, teacher model, or reinforcement learning is used.
- **Results**: SSD improves Qwen3-30B-Instruct from 42.4% to 55.3% pass@1 on LiveCodeBench v6, with gains concentrated on harder problems. The method generalizes across different models and scales.
- **Mechanism**: SSD reshapes token distributions to suppress distractor tails where precision matters (locks) while preserving useful diversity where exploration matters (forks). This alleviates the precision-exploration conflict in LLM decoding.
- **Key Insights**:
  - Training and evaluation temperatures compose multiplicatively, and truncation raises the achievable pass@1 within that band.
  - SSD does not collapse diversity; gains are often larger at pass@5 than at pass@1, indicating preserved generation diversity.
  - Even with poor-quality training data (e.g., high-temperature sampling without truncation), SSD can still improve the model, suggesting that the benefits come from distributional reshaping rather than raw program correctness.
## Links


## Topics

![[topics/Concept/Self Distillation]]

![[topics/Concept/Precision Exploration Conflict]]

![[topics/Concept/Support Compression]]

![[topics/Concept/Within Support Reshaping]]

![[topics/Concept/Effective Temperature]]

![[topics/Concept/Lock and Fork Contexts]]

![[topics/Platform/LiveCodeBench]]

![[topics/Dataset/rSTARcoder]]

![[topics/Library/vLLM]]