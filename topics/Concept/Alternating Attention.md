---
type: Concept
---

Alternating Attention is a feature in ModernBERT that improves processing efficiency by using a combination of global and local attention mechanisms. In this approach, full global attention is used every three layers, while other layers use local attention with a sliding window of 128 tokens. This method reduces computational complexity, allowing ModernBERT to process long input sequences faster. The concept is analogous to reading a book where full awareness of the entire plot is not always necessary; local context is often sufficient, with occasional global context checks for better understanding.