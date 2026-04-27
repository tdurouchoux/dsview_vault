---
type: Concept
---

The precision-exploration conflict refers to the inherent tension in decoding strategies where precision-bound contexts (e.g., syntactic or semantic constraints in code generation) require suppressing low-probability distractors, while exploration-bound contexts (e.g., algorithmic choices) demand preserving diversity among viable alternatives. This conflict arises because a fixed decoding configuration (e.g., temperature) cannot simultaneously optimize for both precision and exploration. Self-distillation (SSD) mitigates this conflict by reshaping the model's token distributions asymmetrically: it suppresses distractors in precision-bound contexts while preserving or even increasing useful entropy in exploration-bound contexts.