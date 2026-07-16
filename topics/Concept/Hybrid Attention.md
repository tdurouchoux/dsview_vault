---
type: Concept
---

Hybrid attention is a mechanism that combines global attention and sliding window attention in transformer models. Global attention attends to the entire context length simultaneously, while sliding window attention focuses on a fixed, localized context window that moves across the input. Inkling employs a hybrid attention scheme with a 5:1 ratio of sliding window to global attention layers. This approach improves computational efficiency by reducing the number of tokens attended to globally, while still allowing the model to capture long-range dependencies through the global attention layers.