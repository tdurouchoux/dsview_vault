---
type: Concept
---

The alignment of a model's confidence in its predictions with their actual accuracy, encompassing techniques and visualizations used to assess and improve reliability, interpretability, and trustworthiness of outputs. This includes graphical representations like calibration curves, which plot mean predicted probabilities against observed event rates for binned predictions, where a well-calibrated model's curve closely follows the diagonal line (y=x). Calibration can be applied during or after training (e.g., via post-hoc methods like temperature scaling) to reduce miscalibration (e.g., overconfidence or underconfidence) and enhance performance, particularly in reducing hallucinations and improving evaluation in language models.