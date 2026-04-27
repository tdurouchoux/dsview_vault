---
type: Concept
---

Support compression is a mechanism in self-distillation where the model's output distribution is constrained to a smaller set of viable tokens (the 'support') by truncation during training. This process removes diffuse tail mass, concentrating probability on a subset of tokens that are more likely to be correct or useful. In code generation, support compression is particularly effective in 'lock' contexts, where only a few tokens are syntactically or semantically valid, and distractors can be aggressively suppressed.