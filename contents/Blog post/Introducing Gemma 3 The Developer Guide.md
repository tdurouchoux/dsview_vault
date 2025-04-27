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

Gemma 3 is the latest iteration of the Gemma open-model family, optimized based on community feedback. Key features include:

- **Multimodal Support**: Capable of handling both vision and language inputs, offering text outputs.
- **Extended Context**: Can manage context windows up to 128,000 tokens.
- **Language Proficiency**: Supports over 140 languages with enhanced multilingual capabilities using a new tokenizer.
- **Model Sizes**: Available in four sizes (1B, 4B, 12B, and 27B), with options for both pre-trained and instruction-tuned versions.

The development process involved advanced techniques including distillation, reinforcement learning from human and machine feedback, and execution feedback, resulting in improvements in math, coding, and instruction following.

Gemma 3 allows users to interleave text with image inputs and has an integrated vision encoder, making it capable of analyzing images and understanding contextual interactions. Notable implementation details include support for high-resolution, non-square images.

For deployment, Gemma 3 is compatible with various tools and platforms, encouraging integration into different projects, and facilitating experimentation through resources like Google AI Studio.
## Links

- [Gemma Documentation](https://ai.google.dev/gemma/docs) : Comprehensive documentation for integrating and using Gemma models.
- [Gemma 3 Model on Kaggle](https://www.kaggle.com/models/google/gemma-3) : Access to the Gemma 3 model weights and related resources on Kaggle.
- [Gemma GitHub Repository](https://github.com/google/gemma.cpp) : Source code and resources for Gemma models on GitHub.
- [Introduction to TPU Docs](https://cloud.google.com/tpu/docs/intro-to-tpu) : Resources and documentation on using Tensor Processing Units (TPUs) for acceleration.
- [Gemma on Google AI Edge](https://developers.googleblog.com/en/gemma-3-on-mobile-and-web-with-google-ai-edge) : Details on deploying Gemma models in mobile and web applications using Google AI Edge.

## Topics

![](topics/Model/Gemma%203)

![](topics/Concept/Multimodality)

![](topics/Concept/Reinforcement%20Learning%20from%20Human%20Feedback%20RLHF)

![](topics/Concept/Distillation)

![](topics/Platform/Google%20AI%20Studio)

![](topics/Library/Hugging%20Face%20Transformers)

![](topics/Concept/Training%20Tokenization)

![](topics/Platform/Vertex%20AI)

![](topics/Concept/Function%20Calling%20in%20AI%20Models)