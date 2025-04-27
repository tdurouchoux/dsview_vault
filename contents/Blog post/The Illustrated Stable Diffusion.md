---
already_read: false
link: https://jalammar.github.io/illustrated-stable-diffusion/
read_priority: 1
relevance: 0
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2022-10-13'
---

https://jalammar.github.io/illustrated-stable-diffusion/
## Summary

Stable Diffusion is a cutting-edge AI image generation model that translates text descriptions into images, functioning as a significant advancement in the realm of generative art. Its architecture comprises several key components:

1. **Text Encoder (ClipText)**: Converts input text into numeric vectors (# of token embeddings) using a Transformer model, effectively capturing the meaning of the text.

2. **Image Information Creator (UNet + Scheduler)**: This component operates in latent space (rather than pixel space), processing the received vectors over multiple steps to generate a latent representation of the image, enhancing speed and performance compared to earlier models.

3. **Image Decoder (Autoencoder)**: Uses the processed latent information to produce the final image.

The process of **diffusion** involves taking an initial noisy representation and gradually refining it step-by-step to align more closely with the text input, transforming random noise into coherent, recognizable images. It learns to remove noise in a way that respects the statistical patterns found in the training dataset.

Stable Diffusion notably enhances efficiency by performing diffusion on compressed (latent) data instead of pixel data, significantly speeding up the image generation process.

The model incorporates text prompts through an attention mechanism, merging text and latent information to guide the denoising process, ensuring that the generated images accurately reflect the specified textual description.

Overall, Stable Diffusion exemplifies the fusion of language and visual generation, marking a remarkable development in AI art creation techniques.
## Links

- [Stable Diffusion - Hugging Face Blog](https://huggingface.co/blog/stable_diffusion) : An overview of Stable Diffusion, its capabilities, and technical insights.
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) : The original paper on latent diffusion models, detailing the algorithms behind image generation.
- [Liliane Weng's Post on Diffusion Models](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) : A comprehensive explanation of diffusion models in machine learning.
- [The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion) : An annotated walkthrough of diffusion models, explaining their workings in detail.
- [Stable Diffusion - Stability AI Blog](https://stability.ai/blog/stable-diffusion-public-release) : Official blog detailing the public release of Stable Diffusion by Stability AI.

## Topics

![](topics/Concept/Diffusion%20Models)

![](topics/Library/CLIP)

![](topics/Model/Stable%20Diffusion)

![](topics/Concept/Latent%20Space)

![](topics/Concept/Text%20to%20Image%20Generation)