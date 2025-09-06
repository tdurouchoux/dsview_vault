---
type: Concept
---

Noise augmentation is a technique used to improve the stability and quality of auto-regressive generation in diffusion models. By adding varying amounts of Gaussian noise to context frames during training, the model learns to correct information from previous frames, preventing error accumulation and maintaining frame quality over long trajectories. This method is critical for ensuring the model's performance remains consistent and high-quality during inference.