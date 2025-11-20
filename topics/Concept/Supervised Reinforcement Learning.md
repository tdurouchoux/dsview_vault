---
type: Concept
---

Supervised Reinforcement Learning (SRL) is a framework that combines elements of supervised learning and reinforcement learning. It reformulates problem-solving as generating a sequence of logical 'actions,' where the model produces an internal reasoning monologue before committing to each action. SRL uses smoother rewards based on the similarity between the model's actions and expert actions extracted from the Supervised Fine-Tuning (SFT) dataset in a step-wise manner. This approach provides richer learning signals and encourages flexible reasoning guided by expert demonstrations, making it effective for solving complex problems that are challenging for traditional methods like Reinforcement Learning with Verifiable Rewards (RLVR) and Supervised Fine-Tuning (SFT).