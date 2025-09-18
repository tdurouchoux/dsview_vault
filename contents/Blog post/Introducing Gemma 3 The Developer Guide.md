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

Gemma 3, the latest version of Google's open-model family, introduces several advanced features based on community feedback. Key updates include multimodality (supporting vision-language input and text outputs), extended context windows (up to 128k tokens), improved multilingual support (over 140 languages), and enhanced capabilities in math, reasoning, and chat. Gemma 3 is available in four sizes (1B, 4B, 12B, and 27B) as both pre-trained and instruction-tuned models.

The model's development involved distillation, reinforcement learning, and model merging, resulting in top performance in math, coding, and instruction following. Gemma 3's vision encoder, based on SigLIP, enables image and video input analysis. The instruct versions maintain the same dialog format as Gemma 2, simplifying the transition.

ShieldGemma 2, a 4B image safety classifier built on Gemma 3, is also introduced for safety moderation of synthetic and natural images.

To get started with Gemma 3, users can experiment directly using Google AI Studio, download model weights from Hugging Face and Kaggle, or integrate the model using preferred tools and frameworks. Multiple deployment options are available, including Google GenAI API, Vertex AI, and Cloud TPU.
## Links

- [Gemma 3 Documentation](https://ai.google.dev/gemma/docs) : Official documentation for Gemma 3, providing detailed information on how to use and integrate the model.
- [Gemma 3 on Hugging Face](https://huggingface.co/collections/google/gemma-3-release-67c6c6f89c4f76621268bb6d) : Collection of Gemma 3 models available on Hugging Face, including various sizes and versions.
- [Gemma 3 Technical Report](https://goo.gle/Gemma3Report) : Technical report detailing the architecture, training process, and performance of Gemma 3.
- [Gemma 3 Models on Kaggle](https://www.kaggle.com/models/google/gemma-3) : Gemma 3 model weights available for download on Kaggle.
- [Gemma 3 Inference Guide](https://ai.google.dev/gemma/docs/inference) : Guide on how to perform inference using Gemma 3 models.

## Topics

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF)]]

![[topics/Concept/Knowledge Distillation)]]

![[topics/Concept/Reinforcement Learning from AI Feedback RLAIF)]]

![[topics/Model/Gemma)]]

![[topics/Concept/SigLIP)]]

![[topics/Concept/ShieldGemma 2)]]

![[topics/Concept/Multimodality)]]

![[topics/Concept/Reinforcement Learning from Execution Feedback RLEF)]]