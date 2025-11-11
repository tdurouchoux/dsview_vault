---
type: Concept
---

Sliding Window Attention is a variation of the attention mechanism used in transformer-based models that restricts the attention context to a smaller window. This approach reduces both memory usage and compute costs by limiting the attention to a fixed-size window of tokens, rather than attending to the entire sequence. Sliding Window Attention was first introduced in the LongFormer paper in 2020 and has since been adopted by models like Mistral and gpt-oss. It is often used in conjunction with other attention mechanisms, such as Grouped Query Attention, and has been shown to have minimal impact on modeling performance while significantly improving efficiency.