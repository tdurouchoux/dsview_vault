---
type: Concept
---

Within-support reshaping is the process by which the model redistributes probability mass among the tokens retained after support compression. This reshaping is guided by the training-time temperature, which smooths or sharpens the distribution within the retained support. In exploration-bound contexts (e.g., 'forks'), within-support reshaping preserves or even increases the entropy among viable alternatives, enabling the model to explore multiple plausible continuations without reopening discarded tails.