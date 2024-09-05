---
already_read: false
link: https://stability.ai/blog/stable-diffusion-v2-release
read_priority: 1
source: null
tags:
- Generative_AI
- Computer_Vision
type: Content
upload_date: '2022-12-15'
---

https://stability.ai/blog/stable-diffusion-v2-release
## Summary

Stable Diffusion 2.0 has been released as an open-source model, building on the success of its predecessor, Stable Diffusion V1. Key improvements include:

1. **New Text-to-Image Models**: Utilizes a new text encoder (OpenCLIP) for enhanced image quality, generating images at resolutions of 512x512 and 768x768 pixels, trained on a filtered subset of the LAION-5B dataset.

2. **Super-resolution Upscaler**: Introduces an Upscaler Diffusion model that increases image resolution by a factor of 4, allowing for image generation up to 2048x2048 pixels.

3. **Depth-to-Image Model**: The depth2img model infers depth from input images, enabling creative applications that maintain structural coherence while transforming images.

4. **Updated Inpainting Model**: A new text-guided inpainting model allows for intelligent and quick modifications of images.

The release emphasizes accessibility, optimized for single GPU use, and aims to foster creativity through open-source collaboration. The models will be available on the Stability AI API Platform and DreamStudio, with ongoing support and updates planned.
## Links

1. [Stable Diffusion Version 2](https://github.com/Stability-AI/stablediffusion) - GitHub repository for the latest version of Stable Diffusion, including model details and access instructions.
2. [Stable Diffusion V1](https://github.com/CompVis/stable-diffusion) - GitHub repository for the original Stable Diffusion model, providing insights into its development and features.
3. [Latent Diffusion Models](https://arxiv.org/abs/2112.10752) - Research paper detailing the foundational concepts behind Latent Diffusion Models, which are integral to the Stable Diffusion framework.
4. [LAION](https://laion.ai/) - Organization that contributed to the development of the datasets used in training Stable Diffusion models, including the LAION-5B dataset.
5. [CompVis Group at LMU Munich](https://ommer-lab.com) - Research group that played a key role in the development of Stable Diffusion, providing background on the team and their work.
## Topics

- [[topics/Concept/Diffusion and Stable Diffusion]]
- [[topics/Model/Text-to-Image Diffusion Models]]
- [[topics/Model/Super-resolution Upscaler Diffusion Models]]
- [[topics/Model/Depth-to-Image Diffusion Model]]
- [[topics/Model/Inpainting Diffusion Model]]