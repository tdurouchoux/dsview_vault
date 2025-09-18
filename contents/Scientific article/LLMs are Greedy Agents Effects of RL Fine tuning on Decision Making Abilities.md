---
already_read: false
link: https://arxiv.org/pdf/2504.16078
read_priority: 3
relevance: 0
source: Data Points
tags:
- Large_Language_Model
type: Content
upload_date: '2025-05-21'
---

https://arxiv.org/pdf/2504.16078
## Summary

The paper "LLMs are Greedy Agents: Effects of RL Fine-tuning on Decision-Making Abilities" by Thomas Schmied et al. investigates the performance of large language models (LLMs) in decision-making scenarios, focusing on multi-armed bandits, contextual bandits, and Tic-tac-toe environments. The study identifies three prevalent failure modes in LLMs: greediness, frequency bias, and the knowing-doing gap. Greediness refers to the model's tendency to favor the best-performing action among a small set of actions seen so far, leading to stagnating action coverage. Frequency bias occurs when the model repeatedly selects the most frequently occurring action in the context, regardless of its reward. The knowing-doing gap highlights the discrepancy between the model's ability to know the correct action and its inability to act on this knowledge effectively.

The authors propose Reinforcement Learning Fine-Tuning (RLFT) on self-generated Chain-of-Thought (CoT) rationales to mitigate these shortcomings. RLFT involves fine-tuning the model using rewards obtained from environment interaction, encouraging the model to refine its reasoning process and favor CoT patterns and actions that lead to higher rewards. The experiments demonstrate that RLFT enhances the decision-making abilities of LLMs by increasing exploration and narrowing the knowing-doing gap. However, the exploration strategies remain sub-optimal, prompting the evaluation of various exploration mechanisms such as epsilon-greedy, context randomization, context summary, self-correction, self-consistency, and exploration bonus. The study also investigates the importance of CoT reasoning, the effectiveness of leveraging expert data, and the benefits of providing the agent with more reasoning tokens.

Key findings include the positive effects of RLFT on exploration and decision-making abilities, the importance of reward shaping for fine-tuning LLMs in decision-making scenarios, and the potential of modern recurrent architectures for faster inference in decision-making tasks. The paper concludes by highlighting the need for further research into frontier models and targeted exploration towards end-goals in more complex environments.
## Links


## Topics

![[topics/Concept/Chain of Thought CoT Reasoning]]

![[topics/Concept/Knowing Doing Gap]]

![[topics/Concept/Frequency Bias]]

![[topics/Concept/Greediness in Decision Making]]

![[topics/Concept/Exploration Mechanisms]]

![[topics/Concept/Reinforcement Learning Fine Tuning RLFT]]