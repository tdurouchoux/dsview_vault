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

🍓 Ichigo: Llama Learns to Talk is a blog post by Menlo Research detailing the development of a new early-fusion, audio and text multimodal model based on Llama3-s. The model, named Ichigo, is designed to listen to human speech and respond in real-time. The research is conducted openly with open-source code, data, and weights.

The post outlines a three-phase training approach to address limitations in the previous Llama3-s-v0.2 checkpoint:

1. **Phase 1: Continual Pre-training on Multilingual Speech**
   - Expanded data from English-only to 7 languages.
   - Training details and parameters are provided, with a focus on multilingual capabilities.
   - MMLU performance dropped significantly after this phase.

2. **Phase 2: Balancing Original Performance and Speech Modality**
   - Aimed to recover the model's general capabilities while enhancing speech-related skills.
   - Increased data size and diversity, optimized training strategies, and improved MMLU performance.
   - Introduced diverse prompts for transcription tasks.

3. **Phase 3: Teach Ichigo To Say “I cannot hear”**
   - Focused on improving user interaction, particularly handling inaudible inputs and multi-turn conversations.
   - Generated synthetic data for inaudible inputs and fine-tuned the model for better context retention.
   - Training details and parameters are provided.

**Results:**
- MMLU performance was recovered and maintained.
- AudioBench evaluation showed competitive performance against other models.
- The model still has limitations, such as weakness to nonsensical audio in multi-turn conversations and unexplored multilingual capabilities.

**Next Steps:**
- Curate better training datasets and establish benchmarks.
- Aim to develop Ichigo as a production-level tool for AI applications.

The post concludes with acknowledgments and an open call for collaboration, encouraging researchers and audio experts to join the effort.
## Links

- [Ichigo Demo](https://ichigo.homebrew.ltd/) : A real-time demo of Ichigo, the MLLM that listens to human speech and talks back.
- [Ichigo on Hugging Face](https://huggingface.co/spaces/jan-hq/Ichigo-llama3.1-s-instruct) : Hugging Face demo of Ichigo, allowing users to interact with the model.
- [Ichigo GitHub Repository](https://github.com/homebrewltd/ichigo) : The official GitHub repository for Ichigo, providing access to the model's code and resources.
- [Qwen2.5-72B Model](https://huggingface.co/Qwen/Qwen2.5-72B-Instruct) : The Qwen2.5-72B model used for generating diverse synthetic answers for inaudible inputs.
- [Torchtune GitHub Repository](https://github.com/pytorch/torchtune) : The GitHub repository for Torchtune, a tool used for training Ichigo.

## Topics

![](topics/Model/Ichigo)

![](topics/Dataset/AudioBench)

![](topics/Concept/Early%20fusion%20multimodal%20model)

![](topics/Concept/Multilingual%20Speech)

![](topics/Concept/WhisperVQ)

![](topics/Library/Torchtune)

![](topics/Concept/Distillabel)