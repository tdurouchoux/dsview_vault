---
type: Concept
---

EmbSum is a content-based recommendation approach that uses precomputed textual summaries of user interests and candidate items. It employs T5-small to encode user interactions and candidate content, and Mixtral-8x22B-Instruct to generate interpretable user interest summaries. These summaries are then used to derive final embeddings, improving the quality and interpretability of recommendations.