---
already_read: false
link: https://arxiv.org/abs/2208.11970
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
type: Content
upload_date: '2022-09-15'
---

https://arxiv.org/abs/2208.11970
## Summary

The paper "Understanding Diffusion Models: A Unified Perspective" by Calvin Luo provides a comprehensive review and unification of diffusion models from both variational and score-based perspectives. Key points include:

1. **Variational Diffusion Models (VDM)**: Derived as a special case of a Markovian Hierarchical Variational Autoencoder, with three key assumptions enabling tractable computation and scalable optimization of the Evidence Lower Bound (ELBO).

2. **Objective Learning**: Optimizing a VDM involves learning a neural network to predict one of three potential objectives:
   - The original source input from any noisified version of it.
   - The original source noise from any noisified input.
   - The score function of a noisified input at any arbitrary noise level.

3. **Score Function Learning**: The paper delves into the implications of learning the score function and connects the variational perspective of diffusion models with the Score-based Generative Modeling perspective through Tweedie's Formula.

4. **Conditional Distribution Learning**: The paper also covers how to learn conditional distributions using diffusion models via guidance.

The paper aims to demystify and unify the understanding of diffusion models, making it a valuable resource for those interested in generative models and their applications.
## Links

- [Cornell University](https://www.cornell.edu/) : Cornell University's official website, which hosts arXiv, a preprint server for research papers in various fields, including computer science and machine learning.
- [Connected Papers](https://www.connectedpapers.com/about) : Connected Papers is a tool that visualizes the network of papers connected to a specific research paper, helping researchers explore related work.
- [NASA ADS](https://ui.adsabs.harvard.edu/abs/arXiv:2208.11970) : NASA ADS (Astrophysics Data System) provides a comprehensive bibliographic database of research papers in astronomy and physics, including this paper on diffusion models.
- [DagsHub](https://dagshub.com/) : DagsHub is a platform for hosting and collaborating on data science and machine learning projects, including version control and experiment tracking.
- [Google Scholar](https://scholar.google.com/scholar_lookup?arxiv_id=2208.11970) : Google Scholar is a widely-used search engine for scholarly literature across various disciplines, including this paper on diffusion models.

## Topics

![[topics/Concept/Diffusion Models]]

![[topics/Concept/Tweedie s Formula]]

![[topics/Concept/Conditional Generation via Guidance]]

![[topics/Concept/Variational Diffusion Models VDM]]

![[topics/Concept/Score based Generative Modeling]]