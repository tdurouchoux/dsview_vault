---
already_read: true
link: https://homebrew.ltd/blog/llama-learns-to-talk
read_priority: 1
relevance: 0
source: 'Alpha Signal '
tags:
- Large_Language_Model
type: Content
upload_date: '2024-10-18'
---

https://homebrew.ltd/blog/llama-learns-to-talk
## Summary

🍓 Ichigo is an early-fusion, audio and text, multimodal model based on Llama3-s, inspired by the Chameleon and Llama Herd papers. It is designed to listen to human speech and respond in real-time. The research is conducted openly with open-source code, data, and weights.

The model underwent a three-phase training process:

1. **Phase 1: Continual Pre-training on Multilingual Speech**
   - Shifted from English-only to 7 languages dataset.
   - Training involved 8064 steps and took 45 hours on 10xA6000s.
   - MMLU performance dropped from 0.69 to 0.42.

2. **Phase 2: Balancing Original Performance and Speech Modality**
   - Focused on recovering model's general capabilities while enhancing speech skills.
   - Increased data size and diversity, maintained English-only instruction dataset.
   - Recovered MMLU performance to 0.63.

3. **Phase 3: Teach Ichigo To Say “I cannot hear”**
   - Fine-tuned the model to handle inaudible inputs and multi-turn conversations.
   - Used synthetic data of random environmental noises and WhisperVQ codebook tokens.
   - Training involved 644 steps and took 3 hours on 8xH100s.

**Results:**
- MMLU performance was recovered and maintained.
- AudioBench evaluation showed improvements in speech capabilities.

**Next Steps:**
- Curate training dataset better, establish benchmarks.
- Aim to develop Ichigo as a production-level tool.

**Acknowledgements:**
- OpenSLR, Torchtune, Whisper, AudioBench, Chameleon, Qwen 2.5, Distilabel, MLS, Yip Jia Qi, Discord Contributors.

**Open Call:**
- Invites LLM researchers and audio experts to collaborate and experiment with Ichigo.
- Encourages open research to accelerate progress in the field.
## Links

- [Ichigo-llama3.1-s-instruct-v0.3-phase-3](https://huggingface.co/homebrewltd/Ichigo-llama3.1-s-instruct-v0.3-phase-3) : Hugging Face model card for Ichigo-llama3.1-s-instruct-v0.3-phase-3, a multimodal model that learns to talk.
- [Ichigo-llama3.1-s-instruct-v0.3-phase-2](https://huggingface.co/homebrewltd/Ichigo-llama3.1-s-instruct-v0.3-phase-2) : Hugging Face model card for Ichigo-llama3.1-s-instruct-v0.3-phase-2, a multimodal model that learns to talk.
- [llama3-s-instruct-v0.2](https://huggingface.co/homebrewltd/llama3-s-instruct-v0.2) : Hugging Face model card for llama3-s-instruct-v0.2, a multimodal model that learns to talk.
- [llama3-s-instruct-v0.3-checkpoint-last](https://huggingface.co/jan-hq/llama3-s-instruct-v0.3-checkpoint-last) : Hugging Face model card for llama3-s-instruct-v0.3-checkpoint-last, a multimodal model that learns to talk.
- [Ichigo-llama3.1-s-instruct](https://huggingface.co/spaces/jan-hq/Ichigo-llama3.1-s-instruct) : Hugging Face Space for Ichigo-llama3.1-s-instruct, a demo of a multimodal model that learns to talk.

## Topics

![[topics/Library/Torchtune]]

![[topics/Dataset/AudioBench]]

![[topics/Model/Ichigo]]

![[topics/Concept/WhisperVQ]]

![[topics/Concept/Early Fusion]]