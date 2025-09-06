---
type: Concept
---

Data pruning is the process of removing similar files from a dataset to ensure unbiased performance evaluation. In the context of phi-1, data pruning involves removing files from the CodeExercises dataset that are similar to those in the HumanEval benchmark. This process helps to investigate the boost in performance observed after training on CodeExercises and to validate the model's performance without contamination from the test set.