---
type: Concept
---

Attention Sinks are special tokens or learned bias logits used in transformer-based models to stabilize attention, particularly in long-context scenarios. These tokens are placed at the start of the sequence and are always attended to, allowing the model to store and retrieve generally useful information about the entire sequence. Attention Sinks were first proposed in the Efficient Streaming Language Models with Attention Sinks paper and have been adopted in models like gpt-oss. They help improve the model's ability to handle long sequences by providing a stable reference point for attention mechanisms.