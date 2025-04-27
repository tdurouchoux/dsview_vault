---
already_read: true
link: https://homebrew.ltd/blog/llama-learns-to-talk
read_priority: 1
relevance: 0
source: 'Alpha Signal '
tags:
- Natural_Language_Processing
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2024-10-18'
---

https://homebrew.ltd/blog/llama-learns-to-talk
## Summary

🍓 Ichigo is an early-fusion multimodal model based on Llama3, developed by Menlo Research to enable speech recognition and response. The project consists of three training phases:

1. **Phase 1: Multilingual Speech Pre-training** - Transitioned from an English-only dataset to seven languages to improve multilingual capabilities, resulting in significant model performance loss (MMLU decreased from 0.69 to 0.42).

2. **Phase 2: Performance Recovery and Speech Modality Enhancement** - Focused on regaining original model performance while enhancing speech-related skills. MMLU score improved from 0.42 to 0.63 through increased training data and optimized data strategies.

3. **Phase 3: User Interaction Fine-tuning** - Aimed at teaching the model to handle inaudible inputs and maintain context in multi-turn conversations. Utilized randomized sound tokens for training inaudible input recognition, while training loss converged at 0.98.

Overall results show that Ichigo successfully recovered MMLU performance and demonstrated improved speech understanding capabilities, although challenges remain in handling nonsensical audio and fully exploring multilingual abilities. Next steps include enhancing the training dataset and creating a production-level tool for AI applications. Collaboration with LLM researchers is encouraged for further development.
## Links

- [Ichigo Llama3 Model on Hugging Face](https://huggingface.co/homebrewltd/Ichigo-llama3.1-s-instruct-v0.3-phase-3) : Access the Ichigo model checkpoint and its associated resources on Hugging Face.
- [AudioBench: A Universal Benchmark for Audio Large Language Models](https://arxiv.org/pdf/2405.09818) : Research paper detailing a benchmark for evaluating audio large language models.
- [Whisper: Robust Speech Recognition via Large-Scale Weak Supervision](https://cdn.openai.com/papers/whisper.pdf) : Research paper on the Whisper model, which has relevance for speech recognition capabilities.
- [Multilingual Librispeech Dataset on Hugging Face](https://huggingface.co/datasets/facebook/multilingual_librispeech) : A dataset for multilingual speech tasks that can be used for training models like Ichigo.
- [Torchtune Documentation](https://github.com/pytorch/torchtune) : Documentation for Torchtune, a library for optimizing PyTorch models, referenced in the context of training Ichigo.

## Topics

![](topics/Model/Llama3%20s%20Ichigo)

![](topics/Platform/Torchtune)

![](topics/Concept/Multimodal%20Models)

![](topics/Dataset/MLLU%20Benchmark%20Dataset)

![](topics/Concept/Speech%20Recognition%20and%20Synthesis)

![](topics/Concept/Audio%20Large%20Language%20Models%20AudioLLMs)

![](topics/Concept/Fine%20tuning%20Techniques)

![](topics/Dataset/MLS%20Dataset)