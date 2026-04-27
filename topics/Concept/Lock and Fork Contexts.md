---
type: Concept
---

Lock and fork contexts are two types of decoding scenarios in code generation that embody the precision-exploration conflict. Lock contexts are precision-bound, where only a few tokens are correct, and the distribution is sharply peaked with a long tail of distractors. Fork contexts are exploration-bound, where multiple tokens represent viable alternatives, and the distribution is more diffuse. Self-distillation reshapes these contexts differently: locks benefit from support compression and tail suppression, while forks benefit from within-support reshaping that preserves diversity.