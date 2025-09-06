---
type: Concept
---

Alternating Attention is a mechanism used in ModernBERT to improve processing efficiency. It alternates between global attention, where every token attends to the full input, and local attention, where each token only attends to the nearest tokens. This approach reduces computational complexity, making it faster to process long input sequences. Conceptually, it mimics how humans read by focusing on immediate context while occasionally considering the broader context.