---
already_read: false
link: https://eugeneyan.com/writing/text-to-image/
read_priority: 1
source: null
tags:
- Deep_Learning
- Natural_Language_Processing
- Generative_AI
type: Content
upload_date: '2022-12-07'
---

https://eugeneyan.com/writing/text-to-image/
## Summary

Text-to-image generation has rapidly evolved with models like DALL·E, DALL·E 2, Imagen, and Stable Diffusion. Key concepts include:

1. **Diffusion**: A process where noise is gradually added to data, and a model learns to reverse this process to generate images from noise. This involves a forward diffusion process (adding noise) and a reverse diffusion process (denoising).

2. **Text Conditioning**: This allows models to generate images based on text prompts. Techniques like CLIP embed text and images in a shared space, enabling the model to learn visual concepts from text.

3. **Classifier Guidance**: This technique enhances image generation by incorporating class information into the diffusion process, improving alignment with text prompts.

4. **Latent Space**: Models like Stable Diffusion operate in a compressed latent space rather than pixel space, which reduces computational costs and allows for faster training and sampling.

The evolution of these models has led to significant advancements in generating high-quality images from text, with ongoing developments in text-to-video and text-to-3D generation.
## Links

1. [Denoising Diffusion Probabilistic Models (DDPM; 2020)](https://arxiv.org/abs/2006.11239) - A foundational paper explaining the diffusion process for generating images from noise.
2. [Learning Transferable Visual Models From Natural Language Supervision (CLIP)](https://arxiv.org/abs/2103.00020) - Introduces a model that learns visual concepts from text, crucial for text-to-image generation.
3. [Zero-Shot Text-to-Image Generation (DALL·E)](https://arxiv.org/abs/2102.12092) - The original paper on DALL·E, a significant model for generating images from textual descriptions.
4. [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598) - Discusses a method for improving image generation quality without needing a separate classifier.
5. [High-Resolution Image Synthesis with Latent Diffusion Models (Stable Diffusion)](https://arxiv.org/abs/2112.10752) - Details the approach of generating images in latent space, which enhances efficiency and accessibility for users.
## Topics

- [[topics/Concept/Diffusion and Stable Diffusion]]
- [[topics/Concept/Text Conditioning]]
- [[topics/Concept/Classifier Guidance]]
- [[topics/Concept/Latent Space]]
- [[topics/Model/DALL·E]]