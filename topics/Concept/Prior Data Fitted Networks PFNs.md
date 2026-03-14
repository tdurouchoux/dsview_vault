---
type: Concept
---

Prior-Data Fitted Networks (PFNs) are a framework for creating machine learning models that can be pre-trained on synthetic data and then applied to new tasks through in-context learning. PFNs define a prior over data-generating processes, allowing the model to sample tasks and datasets, and use a transformer architecture to make predictions based on the provided context data. This approach enables transfer learning for tabular data by integrating over latent tasks, making it applicable across different tabular problems.