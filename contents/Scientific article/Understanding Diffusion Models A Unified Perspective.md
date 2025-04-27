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

The paper "Understanding Diffusion Models: A Unified Perspective" by Calvin Luo explores the capabilities of diffusion models as generative models, especially in text-conditioned image generation tasks like those implemented in Imagen and DALL-E 2. It reviews and unifies the understanding of diffusion models through both variational and score-based perspectives.

Key technical points include:
- Deriving Variational Diffusion Models (VDM) from a Markovian Hierarchical Variational Autoencoder, emphasizing the importance of three core assumptions to enable tractable computation and scalable optimization of the ELBO (Evidence Lower Bound).
- Optimizing a VDM involves training a neural network to predict one of three objectives related to the original source, its noise, or the score function of a noisified input.
- A deeper investigation into learning the score function connects the variational and score-based generative modeling perspectives through Tweedie’s Formula.
- Discusses methods for learning conditional distributions using diffusion models through guidance techniques.

The study contributes to a clearer comprehension and framework for applying diffusion models in machine learning and computer vision.
## Links

- [Papers with Code - Understanding Diffusion Models](https://paperswithcode.com/) : A platform that links research papers to the code implementations to facilitate the understanding and application of diffusion models.
- [Scite - Smart Citations](https://www.scite.ai/) : A smart citation platform that provides insights into how research has been cited and its relevance in the context of diffusion models.
- [Hugging Face - Model Hub](https://huggingface.co/docs/hub/spaces) : An accessible platform for utilizing and sharing machine learning models, including those based on diffusion models.
- [Litmaps](https://www.litmaps.co/) : A visual literature management toolkit that helps researchers find, read, and manage scholarly papers related to machine learning and diffusion models.
- [Connected Papers](https://www.connectedpapers.com/about) : A tool to create a visual graph of papers relevant to a specific research topic, such as diffusion models, helping in understanding the landscape of research.

## Topics

![](topics/Concept/Diffusion%20Models)

![](topics/Concept/Variational%20Diffusion%20Models%20VDM)

![](topics/Concept/Score%20based%20Generative%20Modeling)

![](topics/Concept/Tweedie%20s%20Formula)

![](topics/Concept/Conditional%20Distribution%20Learning)