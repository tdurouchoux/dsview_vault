---
type: Concept
---

Pseudo-labeling is a technique used to leverage unlabeled data by generating labels for it using a pre-trained model. These pseudo-labels can then be used to further train the model, effectively increasing the size of the labeled dataset. This method is particularly useful when obtaining labeled data is expensive or time-consuming. In the context of the provided text, pseudo-labeling is highlighted as a method to improve model robustness and performance by using soft labels (probabilities instead of hard labels) and ensuring that the validation data does not leak information into the training process. This technique is practical with GPU acceleration, making it feasible to run multiple cycles of pseudo-labeling in a shorter time frame.