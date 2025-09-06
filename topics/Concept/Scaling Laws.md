---
type: Concept
---

Scaling laws in the context of dictionary learning refer to the observation that the loss function used during training, a weighted combination of reconstruction mean-squared error (MSE) and an L1 penalty on feature activations, can be used as a proxy for the quality of a dictionary learning run. These laws help in understanding how additional compute improves dictionary learning results and how that compute should be allocated to obtain the highest-quality dictionary possible for a given computational budget. The scaling laws framework for hyperparameter optimization is used to treat dictionary learning as a standard machine learning problem, optimizing the loss function to achieve lower losses with increased compute.