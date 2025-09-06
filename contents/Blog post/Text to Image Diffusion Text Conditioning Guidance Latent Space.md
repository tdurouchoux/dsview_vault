---
already_read: false
link: https://eugeneyan.com/writing/text-to-image/
read_priority: 1
relevance: 0
source: null
tags:
- Deep_Learning
- Computer_Vision
type: Content
upload_date: '2022-12-07'
---

https://eugeneyan.com/writing/text-to-image/
## Summary

The content discusses the rapid advancements in text-to-image generation, focusing on key concepts like diffusion, text conditioning, guidance, and latent space. It starts with the diffusion process, which involves gradually adding noise to data and learning to generate data from noise, as explained in early papers like "Deep Unsupervised Learning using Nonequilibrium Thermodynamics" and "Denoising Diffusion Probabilistic Models (DDPM)." The process includes a forward diffusion step that adds Gaussian noise and a reverse diffusion step that denoises the image, implemented via a neural network.

Text conditioning enables generating images based on text prompts. This is achieved through models like CLIP, which embeds text and images in the same space, and DALL·E, which uses a visual codebook to compress images into tokens. DALL·E 2 and Imagen further refine this process, with Imagen notably using a text encoder not trained on image-caption pairs, demonstrating that large language models can learn useful representations without explicit text-to-image training.

Guidance techniques, such as classifier guidance and classifier-free guidance, enhance the alignment of generated images with text prompts. Classifier guidance uses a classifier's gradients to guide the diffusion process, while classifier-free guidance trains a conditional diffusion model with conditioning dropout, allowing the model to function as either conditional or unconditional based on the guidance scale.

Finally, the content discusses latent space, where diffusion operates on compressed image representations instead of raw pixels. Stable Diffusion uses a variational autoencoder (VAE) to encode images into a lower-dimensional latent space, reducing computational costs and enabling text-to-image generation on consumer-grade hardware. This approach leads to faster training and sampling, making text-to-image generation more accessible.

Overall, the content highlights the evolution of text-to-image models, from basic diffusion to advanced techniques like text conditioning, guidance, and latent space diffusion, showcasing the rapid progress and innovative approaches in this field.
## Links

- [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2209.14792) : This paper discusses how diffusion models can outperform GANs in image synthesis, focusing on classifier-guidance techniques.
- [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2204.06125) : This paper introduces classifier-free guidance, a technique to improve image generation in diffusion models without needing a separate classifier.
- [Stable Diffusion Pipeline](https://huggingface.co/docs/diffusers/api/pipelines/stable_diffusion#diffusers.StableDiffusionPipeline.__call__.guidance_scale) : This documentation provides an overview of the Stable Diffusion pipeline, including the guidance scale parameter for controlling the strength of text prompts.
- [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2006.09011) : This paper introduces CLIP, a model that learns visual concepts from natural language supervision, enabling zero-shot classification and text-to-image generation.
- [How Imagen Actually Works](https://www.assemblyai.com/blog/how-imagen-actually-works/) : This blog post provides an in-depth explanation of how the Imagen text-to-image model works, including its use of a large text encoder and diffusion model.

## Topics

![](topics/Concept/Text%20Conditioning)

![](topics/Concept/Classifier%20Guidance)

![](topics/Concept/Latent%20Space)

![](topics/Concept/Diffusion%20Models)