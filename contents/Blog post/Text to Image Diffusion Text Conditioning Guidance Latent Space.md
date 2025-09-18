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

The content discusses the rapid advancements in text-to-image generation, focusing on key concepts like diffusion, text conditioning, guidance, and latent space.

**Diffusion** involves gradually adding noise to data and learning to generate data from noise. The process includes a forward diffusion that adds Gaussian noise and a reverse diffusion that denoises the data. The Denoising Diffusion Probabilistic Models (DDPM) trains a neural network to predict the noise in images, enabling image generation from pure noise.

**Text Conditioning** allows generating images based on text prompts. Contrastive Language-Image Pre-training (CLIP) embeds text and images in the same space, enabling zero-shot classification. DALL·E and its variants use autoregressive transformers and cross-attention to generate images from text prompts, while Imagen uses a large language model (T5) for text encoding.

**Classifier Guidance** enhances image generation by incorporating text prompts directly into the diffusion process. Classifier-free guidance, a more practical approach, trains a conditional diffusion model with conditioning dropout, allowing the model to function as either a conditional or unconditional model based on the guidance scale.

**Latent Space** involves applying diffusion on image embeddings instead of image pixels. Stable Diffusion compresses images into a lower-dimensional latent representation using a variational autoencoder (VAE), reducing computation and memory requirements. This allows for faster training and sampling, making text-to-image generation accessible on consumer-grade hardware.

The content highlights the rapid progress in text-to-image generation, with recent developments like NVIDIA's eDiff-I and advancements in text-to-video and text-to-3D generation. The fundamentals discussed provide a foundation for understanding current and future advances in text-to-media generation.
## Links

- [Deep Unsupervised Learning using Nonequilibrium Thermodynamics](https://arxiv.org/abs/1503.03585) : The paper that introduced the concept of diffusion in the context of deep learning, inspired by non-equilibrium statistical physics.
- [Denoising Diffusion Probabilistic Models (DDPM)](https://arxiv.org/abs/2006.11239) : A paper that provides a gentler explanation of the diffusion process and introduces the concept of denoising diffusion probabilistic models.
- [Learning Transferable Visual Models From Natural Language Supervision (CLIP)](https://arxiv.org/abs/2102.12092) : A paper that introduces the concept of Contrastive Language-Image Pre-training (CLIP), which embeds text and image in the same space via a projection layer.
- [Zero-Shot Text-to-Image Generation (DALL·E)](https://openai.com/blog/dall-e/) : A blog post that introduces DALL·E, one of the first text-to-image generation models open to the public.
- [High-Resolution Image Synthesis with Latent Diffusion Models (Stable Diffusion)](https://arxiv.org/abs/2112.10741) : A paper that introduces the concept of latent diffusion, which applies diffusion on image embeddings instead of image pixels.

## Topics

![[topics/Concept/Latent Space]]

![[topics/Concept/Diffusion Models]]

![[topics/Concept/Classifier Guidance]]

![[topics/Concept/Text Conditioning]]