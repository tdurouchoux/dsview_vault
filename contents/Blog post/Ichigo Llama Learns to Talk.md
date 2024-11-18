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

🍓 Ichigo is an early-fusion, multimodal model that combines audio and text, developed as part of the Llama3-s checkpoint. The research is open-source, including code, data, and weights. 

The training process consists of three phases:

1. **Continual Pre-training on Multilingual Speech**: Transitioned from an English-only dataset to a multilingual dataset (7 languages) to enhance capabilities. Training involved 8064 steps over 45 hours, with a focus on improving MMLU performance, which initially dropped significantly.

2. **Balancing Original Performance and Speech Modality**: Aimed to recover the model's original capabilities while enhancing speech skills. Data size was increased and diversified, and a new tokenization strategy was implemented. MMLU performance improved from 0.42 to 0.63 after this phase.

3. **Teach Ichigo To Say “I cannot hear”**: Focused on improving user interaction and context retention in multi-turn conversations. The model was trained to recognize inaudible inputs and respond appropriately, using a synthetic dataset of sound patterns.

Results showed recovery in MMLU performance and improvements in speech capabilities, with plans for further benchmarking and dataset curation. Future steps include enhancing multilingual capabilities and developing Ichigo into a production-level tool.
## Links

1. [Whisper: Robust Speech Recognition via Large-Scale Weak Supervision](https://cdn.openai.com/papers/whisper.pdf) - A foundational paper on the Whisper model, which is relevant for understanding the speech recognition capabilities integrated into Ichigo.
2. [AudioBench: A Universal Benchmark for Audio Large Language Models](https://arxiv.org/pdf/2406.16020) - This paper discusses a benchmark designed to evaluate audio large language models, which is pertinent to the evaluation of Ichigo's performance.
3. [The Evolution of Multimodal Model Architectures](https://arxiv.org/pdf/2405.17927) - This paper provides insights into the development of multimodal models, relevant to the architecture of Ichigo.
4. [Torchtune: A PyTorch Library for Efficient Model Training](https://github.com/pytorch/torchtune) - A resource for understanding the training techniques used in Ichigo, particularly the Fully Sharded Data Parallelism.
5. [MMLU: A Benchmark for Evaluating Language Models](https://github.com/EleutherAI/lm-evaluation-harness/blob/0e76386206771143c25b98de977a47cf6055de66/lm_eval/tasks/mmlu/README.md?plain=1#L37) - This link provides details on the MMLU benchmark, which is crucial for assessing the model's performance in various tasks.
## Topics

![](topics/Model/Ichigo)

![](topics/Dataset/Multilingual%20Speech%20Dataset)

![](topics/Product/Torchtune)

![](topics/Concept/Synthetic%20Data%20Generation)

![](topics/Platform/AudioBench)