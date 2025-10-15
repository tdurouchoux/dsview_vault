---
type: Concept
---

Stacking, or stacked generalization, is an ensembling technique that involves training a higher-level model (meta-model) on the outputs of multiple base models. The idea is to combine the strengths of different models to improve overall performance. In the context of the provided text, stacking is highlighted as a powerful technique for capturing complex patterns in the data that individual models might miss. The text mentions two approaches to stacking: using residuals (training a Stage 2 model on what Stage 1 got wrong) and using out-of-fold (OOF) predictions as features for the Stage 2 model. GPU acceleration is noted as a means to make stacking practical for large-scale datasets by speeding up the training and evaluation of multi-level ensembles.