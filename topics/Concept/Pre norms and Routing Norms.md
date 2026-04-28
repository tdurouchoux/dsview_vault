---
type: Concept
---

Pre-norms and Routing Norms are two distinct sets of normalization layers used in Attention Residuals. Pre-norms are applied to the input of each sublayer (e.g., MHA or MLP) to stabilize activations before they enter heavy weight matrices, preventing gradient explosion. Routing norms, on the other hand, are used within the alpha gate to normalize the history database for fair scoring across entries. These norms serve entirely different purposes and must remain separate to allow the model to develop distinct routing strategies for different sublayers.