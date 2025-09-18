---
already_read: false
link: https://huggingface.co/blog/rlhf
read_priority: 1
relevance: 0
source: null
tags:
- Natural_Language_Processing
type: Content
upload_date: '2023-09-21'
---

https://huggingface.co/blog/rlhf
## Summary

Reinforcement Learning from Human Feedback (RLHF) is a method that uses human feedback to optimize language models, aligning them with complex human values. The process involves three main steps: pretraining a language model, gathering data to train a reward model, and fine-tuning the language model with reinforcement learning.

1. **Pretraining Language Models**: RLHF starts with a pretrained language model, which can be fine-tuned on additional text or conditions. The choice of the initial model is not clearly defined, and the design space of options in RLHF training is not thoroughly explored.

2. **Reward Model Training**: The reward model is trained using human preferences. Human annotators rank the generated text outputs from the language model, and these rankings are used to create a scalar reward signal for training. The reward model can be another fine-tuned language model or a model trained from scratch on the preference data.

3. **Fine-tuning with RL**: The language model is fine-tuned using reinforcement learning, specifically the Proximal Policy Optimization (PPO) algorithm. The reward function combines the preference model and a constraint on policy shift, using the Kullback–Leibler (KL) divergence to penalize the RL policy from moving substantially away from the initial pretrained model.

Open-source tools for RLHF include TRL, TRLX, and RL4LMs, which are designed to fine-tune pretrained language models with PPO and other RL algorithms. The future of RLHF involves exploring new RL algorithms, improving the RL optimizer, and addressing the challenges of gathering high-quality human preference data.

Key papers on RLHF include studies on training language models to follow instructions, summarizing text, navigating the web, and fine-tuning dialogue agents. The field is the convergence of multiple fields, including continual learning of instructions and bandit learning from user feedback.
## Links

- [OpenAI Spinning Up PPO](https://spinningup.openai.com/en/latest/algorithms/ppo.html) : OpenAI Spinning Up PPO algorithm explanation.
- [DeepMind GopherCite](https://www.deepmind.com/publications/gophercite-teaching-language-models-to-support-answers-with-verified-quotes) : DeepMind GopherCite: Teaching language models to support answers with verified quotes.
- [OpenAI Instruction Following](https://openai.com/blog/instruction-following/) : OpenAI blog post on instruction following.
- [CarperAI TRLX](https://github.com/CarperAI/trlx) : CarperAI TRLX GitHub repository for RLHF.
- [Hugging Face RL4LMs](https://github.com/allenai/RL4LMs) : Hugging Face RL4LMs GitHub repository for RLHF.

## Topics

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF)]]

![[topics/Concept/Reward Modeling)]]

![[topics/Concept/Kullback Leibler KL Divergence)]]

![[topics/Concept/Proximal Policy Optimization PPO)]]

![[topics/Concept/Fine tuning with Reinforcement Learning)]]

![[topics/Concept/Open source Tools for RLHF)]]

![[topics/Concept/Pre training)]]