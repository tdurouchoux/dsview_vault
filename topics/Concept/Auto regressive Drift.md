---
type: Concept
---

Auto-regressive drift refers to the phenomenon where the quality of generated frames degrades over time due to error accumulation in auto-regressive sampling. This occurs because the domain shift between training with teacher-forcing and auto-regressive sampling leads to instability. Noise augmentation is a key technique to mitigate auto-regressive drift, allowing the model to correct information from previous frames and maintain quality over long trajectories. Addressing auto-regressive drift is essential for achieving stable and high-quality frame generation in real-time applications.