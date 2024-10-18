---
already_read: true
link: https://homebrew.ltd/blog/llama-learns-to-talk
read_priority: 1
source: 'Alpha Signal '
tags:
- Natural_Language_Processing
- Generative_AI
type: Content
upload_date: '2024-10-18'
---

https://homebrew.ltd/blog/llama-learns-to-talk
## Summary

🍓 Ichigo is an early-fusion multimodal model that combines audio and text, developed as part of the llama3-s checkpoint. The research is open-source, including code, data, and weights. The model underwent three training phases to enhance its multilingual capabilities and speech understanding.

**Training Phases:**
1. **Phase 1:** Focused on continual pre-training with a multilingual dataset (7 languages) to improve alignment with the original LLM. Training involved 8064 steps, resulting in a significant drop in MMLU performance from 0.69 to 0.42.
   
2. **Phase 2:** Aimed to balance original performance and speech capabilities. Data size increased from 0.92M to 1.89M samples, and MMLU performance improved from 0.42 to 0.63. The training involved optimizing data types and interleaving different modalities.

3. **Phase 3:** Fine-tuned the model for better user interaction, particularly in recognizing inaudible inputs and improving context retention in multi-turn conversations. The training included generating synthetic "inaudible" data and enhancing the model's ability to respond appropriately.

**Results:** 
- MMLU performance was recovered and maintained post-training.
- The model was evaluated using AudioBench, showing competitive performance against other models.

**Next Steps:** 
- Further dataset curation and development of a synthetic data pipeline.
- Long-term goals include creating a production-level tool for AI applications.

The project encourages collaboration from researchers and audio experts to advance the model's capabilities.
## Links

1. [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://arxiv.org/pdf/2405.09818) - A research paper discussing the early-fusion approach in multimodal models, which inspired the development of Ichigo.
2. [Llama Herd](https://arxiv.org/pdf/2407.21783) - A paper that provides insights into the Llama model family, relevant to understanding the architecture behind Ichigo.
3. [AudioBench: A Universal Benchmark for Audio Large Language Models](https://arxiv.org/pdf/2406.16020) - This paper presents a benchmark designed to evaluate audio large language models, which is crucial for assessing Ichigo's performance.
4. [Whisper: Robust Speech Recognition via Large-Scale Weak Supervision](https://cdn.openai.com/papers/whisper.pdf) - A foundational paper on speech recognition that informs the methodologies used in Ichigo's training.
5. [Torchtune](https://github.com/pytorch/torchtune) - A library that provides tools for tuning PyTorch models, relevant for the training strategies employed in Ichigo.
## Topics

- [[topics/Model/Ichigo]]
- [[topics/Concept/Multimodal AI and Processing]]
- [[topics/Library/Torchtune]]
- [[topics/Platform/Hugging Face]]