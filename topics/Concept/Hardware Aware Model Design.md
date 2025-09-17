---
type: Concept
---

Hardware-Aware Model Design is an approach in ModernBERT that optimizes the model architecture for specific hardware constraints. This involves balancing deep and narrow model designs with wide and shallow ones to maximize performance across a range of GPUs. By defining target GPUs, model sizes, and performance constraints, ModernBERT achieves efficient hardware utilization. This design ensures that the model runs well on common inference GPUs, such as RTX 3090/4090, A10, T4, and L4, making it practical for real-world applications.