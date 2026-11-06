---
type: Concept
---

A machine learning architecture where a model consists of multiple specialized sub-models (experts) and a routing mechanism that dynamically selects a subset of experts to process each input token. This approach reduces computational cost by activating only a fraction of the model's parameters per token while retaining the capacity of a larger model. The architecture is employed in large language models (e.g., Mistral Large 3, Llama 4) to enhance inference efficiency and reduce serving costs, leveraging sparse activation of experts (e.g., Kolibri-1 uses 384 experts per layer, selecting 6 per token) and stacking Transformer decoder blocks with dense initial layers followed by mixtures of experts.