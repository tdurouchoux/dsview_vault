---
already_read: false
link: https://developers.googleblog.com/en/introducing-gemma3/
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2025-03-13'
---

https://developers.googleblog.com/en/introducing-gemma3/
## Summary

Gemma 3, the latest open-model family from Google, introduces several advanced features based on community feedback. Key updates include multimodality (supporting vision-language input and text outputs), extended context windows (up to 128k tokens), improved multilingual support (over 140 languages), and enhanced capabilities in math, reasoning, and chat. Gemma 3 is available in four sizes (1B, 4B, 12B, and 27B) as both pre-trained and instruction-tuned models.

The model's development involved distillation, reinforcement learning, and model merging, resulting in top performance in math, coding, and instruction following. Gemma 3's vision encoder, based on SigLIP, enables image and video input analysis. The instruct versions maintain the same dialog format as Gemma 2, simplifying the transition.

ShieldGemma 2, a 4B image safety classifier built on Gemma 3, is also introduced for safety moderation of synthetic and natural images.

To get started with Gemma 3, users can experiment directly in Google AI Studio, download model weights from Hugging Face and Kaggle, or integrate the model using various tools and frameworks. Deployment options include Google GenAI API, Vertex AI, Cloud Run, Cloud TPU, and Cloud GPU.
## Links

- [Gemma 3 Documentation](https://ai.google.dev/gemma/docs) : Official documentation for Gemma 3, providing detailed information on how to use and integrate the model.
- [Gemma 3 Models on Hugging Face](https://huggingface.co/collections/google/gemma-3-release-67c6c6f89c4f76621268bb6d) : Collection of Gemma 3 models available on Hugging Face, including various sizes and versions for different use cases.
- [Gemma 3 on Kaggle](https://www.kaggle.com/models/google/gemma-3) : Gemma 3 models hosted on Kaggle, providing access to model weights and resources for experimentation and fine-tuning.
- [Gemma 3 Technical Report](https://goo.gle/Gemma3Report) : Comprehensive technical report detailing the architecture, training process, and performance of Gemma 3.
- [Gemma 3 Inference Guide](https://gemma-llm.readthedocs.io/en/latest/) : Guide on how to perform inference using Gemma 3, including code examples and best practices.

## Topics

![](topics/Model/Gemma)

![](topics/Concept/Multimodality)

![](topics/Concept/Reinforcement%20Learning%20from%20AI%20Feedback%20RLAIF)

![](topics/Concept/Reinforcement%20Learning%20from%20Execution%20Feedback%20RLEF)

![](topics/Library/JAX%20Framework)

![](topics/Concept/Reinforcement%20Learning%20from%20Human%20Feedback%20RLHF)