---
type: Tool
---

Sparse Autoencoders (SAEs) are a type of neural network used to decompose the activations of a model into more interpretable pieces. They consist of an encoder that maps the activity to a higher-dimensional layer via a learned linear transformation followed by a ReLU nonlinearity, and a decoder that attempts to reconstruct the model activations via a linear transformation of the feature activations. The model is trained to minimize a combination of reconstruction error and an L1 regularization penalty on the feature activations, which incentivizes sparsity. This allows the SAE to provide an approximate decomposition of the model’s activations into a linear combination of 'feature directions' with coefficients equal to the feature activations.