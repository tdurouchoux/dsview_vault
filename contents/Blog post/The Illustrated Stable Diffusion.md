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

- **Diffusion Process**: The model generates images through a step-by-step diffusion process, starting with random noise and gradually refining it based on the input text. This involves training a noise predictor to remove noise from images, effectively learning to generate aesthetically pleasing images.

- **Latent Space**: The model operates in latent space, which allows for faster processing and improved efficiency compared to traditional pixel-based methods.

- **Text Conditioning**: The integration of text into the image generation process is achieved through attention layers in the UNet, allowing the model to generate images that align with the provided text prompts.

- **Training**: The model is trained on a large dataset of images and their corresponding captions, enabling it to learn the relationships between visual elements and textual descriptions.

Overall, the article emphasizes the innovative architecture of Stable Diffusion and its implications for the future of AI-generated art.
## Links

1. [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2205.11487) - The original paper detailing the Latent Diffusion Models, which are foundational to understanding Stable Diffusion.
2. [The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion) - A comprehensive guide that annotates the diffusion model, providing insights into its workings and applications.
3. [Stable Diffusion - What, Why, How?](https://www.youtube.com/watch?v=J87hffSMB60) - A video that explains the Stable Diffusion model, its purpose, and its functionality in a visual format.
4. [Large OpenCLIP](https://laion.ai/blog/large-openclip/) - A blog post discussing the OpenCLIP model, which is relevant for understanding the text encoding component used in Stable Diffusion.
5. [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) - An in-depth article that explores diffusion models, their principles, and their applications in machine learning.
## Topics

![](topics/Concept/Stable%20Diffusion)

![](topics/Model/CLIP)

![](topics/Model/UNet)

![](topics/Model/Autoencoder)

![](topics/Concept/Latent%20Space)