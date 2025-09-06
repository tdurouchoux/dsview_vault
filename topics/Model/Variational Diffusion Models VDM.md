---
type: Model
---

Variational Diffusion Models (VDM) are a specific type of diffusion model derived as a special case of a Markovian Hierarchical Variational Autoencoder. They rely on three key assumptions that enable tractable computation and scalable optimization of the Evidence Lower Bound (ELBO). VDMs are optimized by learning a neural network to predict one of three potential objectives: the original source input from any arbitrary noisification of it, the original source noise from any arbitrarily noisified input, or the score function of a noisified input at any arbitrary noise level.