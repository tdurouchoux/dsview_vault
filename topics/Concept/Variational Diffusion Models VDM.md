---
type: Concept
---

Variational Diffusion Models (VDM) are a specific type of diffusion model derived as a special case of a Markovian Hierarchical Variational Autoencoder. They enable tractable computation and scalable optimization of the Evidence Lower Bound (ELBO) through three key assumptions. VDMs can be optimized to learn one of three potential objectives: the original source input from any noisified version, the original source noise from any noisified input, or the score function of a noisified input at any noise level.