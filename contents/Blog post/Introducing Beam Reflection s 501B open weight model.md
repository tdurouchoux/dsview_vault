---
already_read: true
link: https://reflection.ai/blog/introducing-beam
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Large_Language_Model
- Deep_Learning
- Model_evaluation
type: Content
upload_date: '2026-11-06'
---

https://reflection.ai/blog/introducing-beam

## Summary

Reflection AI introduces Beam, a 501B-parameter open-weight sparse Mixture-of-Experts model optimized for coding, reasoning, and agentic tasks with exceptional inference efficiency.

**Model Overview**
- 501B total parameters, 23B active, sparse MoE architecture.
- Pretrained on 23.8T high-quality tokens (web, licensed, proprietary).
- Competitive with larger open models (e.g., GLM 5.2, Qwen 3.8-Max) on coding/agentic benchmarks.
- 3–4× more inference-efficient than GLM-5.2, significantly more efficient than 2T+ parameter models.

**Performance Highlights**
- Top scores on SWEBench (v1: 65.5, Pro v2-Hard: 77.2), Terminal Bench v2.1 (80.1), and DeepSWE v1.1 (44.4).
- Strong reasoning: AIME 2026 (97.8%), GPQA Diamond (90.5%), HLE (no tools: 36.2%, with tools: 51.2%).
- Efficient tool use: MCP Atlas (78.7%), BrowseComp (77.4%), DeepSearchQA (80.1%).

**Reinforcement Learning (RL) at Scale**
- 100M+ rollouts over 4 weeks on 10.5K NVIDIA GB300 GPUs.
- 1.3B sandboxes, 256K max context length, 1M+ high-quality environments.
- Asynchronous policy gradients with stability under 1-day staleness.
- Controllable reasoning effort: balances token efficiency and performance.

**Pretraining & Infrastructure**
- 4-week pretraining on 6,144 NVIDIA GB300 NVL72 GPUs, 92.3% goodput.
- Near-uniform MoE expert utilization (1.04× max load).
- Stable residual stream norms across 52 layers via depth-based scaling + SandwichNorm.
- Data curation: 95% of raw web tokens filtered, 1.8T high-quality tokens retained (87% of web-code tokens).
- Midtraining extends context to 1M tokens, focusing on reasoning-rich, long-horizon tasks.

**Safety & Alignment**
- Multi-teacher on-policy distillation (MOPD) merges RL and safety teachers.
- 3-tier principles: (1) non-negotiable rules, (2) consistent qualities, (3) default interaction style.
- Deliberative alignment + adversarial training to reduce harmful compliance/over-refusals.
- Predictable RL gains (r=0.79 correlation with forecasted rewards).

**Release & Roadmap**
- Weights (Apache 2.0), technical report, and developer tools releasing later this month.
- Early access via waitlist; full ecosystem integrations planned.
- Next models already in training to push open-weight frontier further.

## Links

- [Beam Model Technical Report](https://reflection.ai/documents/beam-model-tech-report) : A detailed technical report on Beam, including its architecture, training methodology, performance benchmarks, and safety evaluations. This is a critical resource for understanding the model's capabilities and innovations.
- [Beam Model Card on Hugging Face](https://huggingface.co/collections/reflection/beam-10) : The official model card for Beam on Hugging Face, providing essential details about the model's weights, usage instructions, and technical specifications.
- [Reflection AI Documentation Hub](https://developers.reflection.ai/) : Comprehensive documentation for developers working with Reflection AI's models, including API references, integration guides, and best practices for using Beam.
- [Beam Platform API](https://platform.reflection.ai/) : The official API endpoint for accessing and interacting with the Beam model, enabling developers to integrate Beam into their applications and workflows.


## Topics

![[topics/Model/Beam]]

![[topics/Tool/NVIDIA GB300 GPUs]]

![[topics/Concept/SWE bench]]

![[topics/Dataset/Terminal Bench]]

![[topics/Dataset/AIME 2026]]

![[topics/Concept/Multi Teacher On Policy Distillation MOPD]]

![[topics/Concept/Apache 2 0 License]]

![[topics/Platform/Hugging Face]]

![[topics/Concept/Mixture of Experts MoE]]

![[topics/Concept/Reinforcement Learning from Human Feedback RLHF]]