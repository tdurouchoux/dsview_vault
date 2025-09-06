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

2. **Objectives**: Optimizing a VDM involves learning a neural network to predict one of three potential objectives: the original source input from any noisified version, the original source noise from any noisified input, or the score function of a noisified input at any noise level.

3. **Score Function**: The paper delves into learning the score function and connects the variational perspective of diffusion models with the Score-based Generative Modeling perspective through Tweedie's Formula.

4. **Conditional Distribution**: The paper also covers how to learn a conditional distribution using diffusion models via guidance.

The paper aims to demystify and unify the understanding of diffusion models, which are currently state-of-the-art in text-conditioned image generation tasks.
## Links

- [arXiv Bibliographic Explorer](https://info.arxiv.org/labs/showcase.html#arxiv-bibliographic-explorer) : The arXiv Bibliographic Explorer is a tool that provides bibliographic and citation tools for arXiv articles. It allows users to explore the bibliographic information of papers hosted on arXiv, including citations, references, and related works.
- [Semantic Scholar](https://api.semanticscholar.org/arXiv:2208.11970) : Semantic Scholar is a search engine for scientific literature that uses AI to extract and display key information from research papers. It provides a summary of the paper, including citations, references, and related papers.
- [Google Scholar](https://scholar.google.com/scholar_lookup?arxiv_id=2208.11970) : Google Scholar is a widely-used search engine for scholarly literature across various disciplines. It indexes a wide range of publications, including articles, theses, books, abstracts, and court opinions, from academic publishers, professional societies, online repositories, universities, and other websites.

## Topics

![](topics/Model/Variational%20Diffusion%20Models%20VDM)

![](topics/Concept/Score%20based%20Generative%20Modeling)

![](topics/Concept/Diffusion%20Models)