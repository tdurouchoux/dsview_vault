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

- **Variational Diffusion Models (VDM)**: The paper derives VDM as a specific case of a Markovian Hierarchical Variational Autoencoder, highlighting three key assumptions that facilitate computation and optimization of the Evidence Lower Bound (ELBO).
  
- **Learning Objectives**: It establishes that optimizing a VDM involves training a neural network to predict one of three objectives: the original input from a noisified version, the original noise from a noisified input, or the score function of a noisified input at any noise level.

- **Score Function Learning**: The paper delves into the implications of learning the score function and connects the variational perspective with the Score-based Generative Modeling perspective using Tweedie's Formula.

- **Conditional Distribution Learning**: It also discusses methods for learning conditional distributions using diffusion models through guidance.

Overall, the work aims to clarify the theoretical foundations and practical applications of diffusion models in machine learning and computer vision.
## Links

1. [Papers with Code](https://paperswithcode.com/) - A platform that provides a collection of machine learning papers along with their code implementations, useful for understanding and replicating research findings.
2. [Semantic Scholar](https://www.scite.ai/) - A research tool that helps users find and understand scientific literature, offering insights into how papers are cited and their impact.
3. [CatalyzeX](https://www.catalyzex.com) - A resource for finding code implementations related to academic papers, particularly in the field of machine learning.
4. [Hugging Face](https://huggingface.co/docs/hub/spaces) - A popular platform for sharing and using machine learning models, including those related to generative models like diffusion models.
5. [arXiv](https://arxiv.org/) - A repository of electronic preprints (known as e-prints) across various fields, including computer science and machine learning, where the paper can be accessed.
## Topics

![](topics/Concept/Diffusion%20Models)

![](topics/Concept/Variational%20Diffusion%20Models%20VDM)

![](topics/Concept/Score%20based%20Generative%20Modeling)

![](topics/Concept/Tweedie%20s%20Formula)

![](topics/Concept/Conditional%20Distribution%20Learning)