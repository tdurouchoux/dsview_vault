---
already_read: true
link: https://developers.googleblog.com/en/introducing-gemma-3-270m/
read_priority: 0
relevance: 4
source: Data Points
tags:
- Large_Language_Model
type: Content
upload_date: '2025-09-17'
---

https://developers.googleblog.com/en/introducing-gemma-3-270m/
## Summary

Gemma 3 270M is a compact, 270-million parameter model designed for task-specific fine-tuning, offering strong instruction-following and text structuring capabilities. Key features include:

- **Compact Architecture**: 270 million parameters, with 170 million for embeddings and 100 million for transformer blocks, supporting a large vocabulary of 256k tokens.
- **Energy Efficiency**: Low power consumption, using just 0.75% of the battery for 25 conversations on a Pixel 9 Pro SoC.
- **Instruction Following**: Released with an instruction-tuned model for general instructions.
- **Quantization**: Quantization-Aware Trained (QAT) checkpoints available for INT4 precision with minimal performance degradation.

**Use Cases**:
- High-volume, well-defined tasks like sentiment analysis, entity extraction, and compliance checks.
- Cost-effective and fast inference on lightweight infrastructure or on-device.
- Rapid fine-tuning and deployment for quick iteration.
- Privacy-focused applications running entirely on-device.
- Creating a fleet of specialized task models.

**Getting Started**:
- Download the model from Hugging Face, Ollama, Kaggle, LM Studio, or Docker.
- Try the model on Vertex AI or with popular inference tools.
- Fine-tune using tools like Hugging Face, UnSloth, and JAX.
- Deploy the specialized model anywhere, from local environments to Google Cloud Run.

Gemma 3 270M is designed to empower developers to build smarter, faster, and more efficient AI solutions.
## Links

- [Gemma 3 270M Model on LM Studio](https://lmstudio.ai/models/google/gemma-3-270m) : Access the Gemma 3 270M model on LM Studio for running and fine-tuning.
- [UnSloth Guide for Gemma 3](https://docs.unsloth.ai/basics/gemma-3-how-to-run-and-fine-tune) : A guide on how to run and fine-tune Gemma 3 models using UnSloth.
- [Gemma 3 270M on Hugging Face](https://huggingface.co/collections/google/gemma-3-release-67c6c6f89c4f76621268bb6d) : Collection of Gemma 3 models and resources on Hugging Face.
- [Gemma 3 270M Instruction-Tuned Model](https://huggingface.co/litert-community/gemma-3-270m-it) : The instruction-tuned version of the Gemma 3 270M model available on Hugging Face.
- [Google Cloud Run Documentation for Gemma](https://cloud.google.com/run/docs/run-gemma-on-cloud-run) : Documentation on how to run Gemma models on Google Cloud Run.

## Topics

![[topics/Model/Gemma]]