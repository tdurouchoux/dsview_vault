---
already_read: false
link: https://jalammar.github.io/illustrated-stable-diffusion/
read_priority: 1
source: null
tags:
- Generative_AI
- Computer_Vision
type: Content
upload_date: '2022-10-13'
---

https://jalammar.github.io/illustrated-stable-diffusion/
## Summary

The Illustrated Stable Diffusion by Jay Alammar provides a comprehensive overview of the Stable Diffusion model, a significant advancement in AI image generation that allows users to create images from text descriptions. Key points include:

- **Model Components**: Stable Diffusion consists of three main components: 
  1. **ClipText**: A Transformer model that encodes text into numerical representations (token embeddings).
  2. **UNet + Scheduler**: This component processes information in latent space, enhancing performance by operating on compressed data rather than pixel images.
  3. **Autoencoder Decoder**: Converts processed information into the final image.

- **Diffusion Process**: The model generates images through a step-by-step diffusion process, which involves adding noise to images and then predicting and removing that noise to create clearer images. This process is trained using a dataset of images and their corresponding captions.

- **Latent Space**: To improve speed and efficiency, the diffusion process operates in a compressed latent space, allowing for faster image generation.

- **Text Conditioning**: The model incorporates text by adjusting the noise predictor to use text embeddings, enhancing the relevance of generated images to the input prompts.

- **Training**: The model is trained on a large dataset of images and captions, allowing it to learn the relationships between visual elements and textual descriptions.

Overall, the article emphasizes the innovative architecture of Stable Diffusion and its implications for AI-driven art creation, highlighting the importance of both the text and image components in generating high-quality visuals.
## Links

1. [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) - A foundational paper that describes the principles behind diffusion models used in image generation.
2. [Google Imagen paper by Saharia et. al.](https://arxiv.org/abs/2205.11487) - A research paper detailing the Google Imagen model, which is relevant to understanding advancements in diffusion models.
3. [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) - An informative blog post that provides an overview of diffusion models and their applications in machine learning.
4. [Stable Diffusion with 🧨 Diffusers](https://huggingface.co/blog/stable_diffusion) - A blog post that discusses the implementation and usage of Stable Diffusion models.
5. [High-Resolution Image Synthesis with Latent Diffusion Models](https://ommer-lab.com/research/latent-diffusion-models/) - A resource that explores the techniques and methodologies behind latent diffusion models for high-resolution image synthesis.
## Topics

- [[topics/Model/Stable Diffusion]]
- [[topics/Model/Diffusion Models]]
- [[topics/Model/CLIP]]
- [[topics/Model/UNet]]
- [[topics/Model/Autoencoder]]