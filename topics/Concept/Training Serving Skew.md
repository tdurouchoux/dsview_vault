---
type: Concept
---

Training-Serving Skew refers to the discrepancy between the performance of a machine learning model during training and its performance when deployed in a production environment. This skew can arise due to differences in the data distribution, feature representation, or system behavior between the training and serving phases. Addressing training-serving skew is crucial for ensuring that the model performs consistently and reliably in real-world scenarios. Techniques to mitigate this skew include logging features at serving time, importance weighting of sampled data, and regular monitoring of model performance.