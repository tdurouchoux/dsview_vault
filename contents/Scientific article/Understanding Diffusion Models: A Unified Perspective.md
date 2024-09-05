---
already_read: false
link: https://arxiv.org/abs/2208.11970
read_priority: 1
source: null
tags:
- Generative_AI
- Computer_Vision
type: Content
upload_date: '2022-09-15'
---

https://arxiv.org/abs/2208.11970
## Summary

The paper "Understanding Diffusion Models: A Unified Perspective" by Calvin Luo reviews and unifies the understanding of diffusion models, which are prominent in generative modeling, particularly in text-conditioned image generation (e.g., Imagen, DALL-E 2). 

Key points include:

- **Variational Diffusion Models (VDM)**: The paper derives VDM as a specific case of a Markovian Hierarchical Variational Autoencoder, highlighting three assumptions that facilitate computation and optimization of the Evidence Lower Bound (ELBO).
- **Learning Objectives**: It establishes that optimizing a VDM involves training a neural network to predict one of three objectives: the original input from a noisified version, the original noise from a noisified input, or the score function of a noisified input at any noise level.
- **Score Function Learning**: The paper delves into the implications of learning the score function and connects the variational and score-based perspectives of diffusion models through Tweedie's Formula.
- **Conditional Distribution Learning**: It also discusses methods for learning conditional distributions using diffusion models via guidance.

Overall, the work aims to clarify the theoretical foundations and practical applications of diffusion models in machine learning and computer vision.
## Links

no links
## Topics

- [[topics/Model/Diffusion Models]]
- [[topics/Concept/Variational Diffusion Models (VDM)]]
- [[topics/Concept/Score-based Generative Modeling]]
- [[topics/Concept/Tweedie's Formula]]
- [[topics/Concept/Conditional Distribution Learning]]