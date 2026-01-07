---
already_read: false
link: https://huggingface.co/blog/hf-skills-training-codex
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
- AI_agent
type: Content
upload_date: '2026-01-07'
---

https://huggingface.co/blog/hf-skills-training-codex
## Summary

The content discusses the open-sourcing of AI models by Codex and its integration with Hugging Face Skills for end-to-end machine learning experiments. Key points include:

- **Codex and Hugging Face Skills**: Codex, an AI coding agent, uses Hugging Face Skills for tasks like fine-tuning models, evaluating checkpoints, and publishing models to the Hub.
- **End-to-End Experiments**: Codex can handle the full lifecycle of model fine-tuning, including dataset validation, hardware selection, training, monitoring, and model conversion.
- **Setup and Installation**: Requires a Hugging Face account with a paid plan, Codex installation, and authentication with Hugging Face.
- **First AI Experiment**: Example of fine-tuning a model using the open-r1/codeforces-cots dataset and evaluating it with the openai_humaneval benchmark.
- **Training Report**: Codex maintains an up-to-date training report, tracking progress, logs, and evaluation results.
- **Dataset Validation**: Codex validates dataset formats and can preprocess datasets if needed.
- **Hardware and Cost**: Codex selects hardware based on model size, with options ranging from t4-small for tiny models to a10g-large for medium models.
- **What's Next**: Encourages users to experiment with fine-tuning models on their own datasets and explore different training methods.

The content also provides resources for further reading and learning about Codex and Hugging Face Skills.
## Links

- [Hugging Face Skills Repository](https://github.com/huggingface/skills) : The Hugging Face Skills repository contains skills for Machine Learning and AI tasks such as training or evaluating models.
- [Hugging Face Trackio Documentation](https://huggingface.co/docs/trackio) : Trackio is a real-time training monitoring tool that helps review, explain, and act on live training metrics.
- [OpenAI Codex Documentation](https://developers.openai.com/codex/) : Documentation for OpenAI's Codex, an AI coding agent that assists in development workflows.

## Topics

![[topics/Model/Qwen3 0 6B]]

![[topics/Concept/Supervised Fine Tuning]]

![[topics/Concept/GGUF GGML Format]]

![[topics/Concept/Trackio]]

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF]]

![[topics/Concept/Direct Preference Optimization DPO]]

![[topics/Concept/LoRA Low Rank Adaptation]]

![[topics/Concept/Model Context Protocol MCP]]