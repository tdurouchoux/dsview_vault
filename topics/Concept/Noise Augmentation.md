---
type: Concept
---

Noise augmentation is a technique used to stabilize auto-regressive generation in diffusion models. By adding varying amounts of Gaussian noise to context frames during training, the model learns to correct information sampled in previous frames. This technique is critical for preserving frame quality over long trajectories and preventing divergence in auto-regressive sampling. Noise augmentation allows the model to generate high-quality frames even when sampling with minimal denoising steps, making it suitable for real-time applications.