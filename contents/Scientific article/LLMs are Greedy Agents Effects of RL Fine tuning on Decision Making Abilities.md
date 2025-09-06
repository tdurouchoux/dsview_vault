---
already_read: false
link: https://arxiv.org/pdf/2504.16078
read_priority: 3
relevance: 0
source: Data Points
tags:
- Large_Language_Model
- AI_agent
- Natural_Language_Processing
type: Content
upload_date: '2025-05-21'
---

https://arxiv.org/pdf/2504.16078
## Summary

The paper "LLMs are Greedy Agents: Effects of RL Fine-tuning on Decision-Making Abilities" by Thomas Schmied et al. explores the suboptimal decision-making abilities of Large Language Models (LLMs) and investigates the effects of Reinforcement Learning (RL) fine-tuning on these abilities. The study identifies three prevalent failure modes in LLMs: greediness, frequency bias, and the knowing-doing gap. Greediness refers to the model's tendency to favor the best-performing action among a small set of actions seen so far, leading to stagnating action coverage. Frequency bias occurs when the model repeatedly selects the most frequently occurring action in the context, regardless of its reward. The knowing-doing gap is characterized by the model's inability to act on the knowledge it possesses, often prioritizing greedy actions over optimal ones.

The authors propose Reinforcement Learning Fine-Tuning (RLFT) on self-generated Chain-of-Thought (CoT) rationales to mitigate these shortcomings. RLFT involves fine-tuning the model using rewards obtained from environment interaction, encouraging the model to refine its reasoning process and favor actions that lead to higher rewards. The study demonstrates that RLFT enhances the decision-making abilities of LLMs by increasing exploration and narrowing the knowing-doing gap. However, the exploration strategies of LLMs remain suboptimal compared to traditional bandit algorithms.

The paper also evaluates various exploration mechanisms, such as epsilon-greedy, context randomization, context summary, self-correction, self-consistency, and exploration bonus, to improve the fine-tuning performance of LLMs. The results indicate that providing sufficient information about the sub-optimality of actions enables LLMs to select actions more appropriately, underscoring their exploration shortcomings.

Additionally, the study highlights the importance of reward shaping for fine-tuning LLMs in decision-making scenarios. The authors conduct experiments on multi-armed bandits, contextual bandits, and Tic-tac-toe environments, demonstrating the effectiveness of RLFT in improving the performance of LLMs in these tasks. The paper concludes by discussing the limitations of the study and suggesting future research directions, such as evaluating the exploration abilities of LLMs in more complex environments and high-stakes scenarios.
## Links


## Topics

![](topics/Concept/Reinforcement%20Learning%20Fine%20Tuning%20RLFT)

![](topics/Concept/Chain%20of%20Thought%20CoT%20Reasoning)

![](topics/Concept/Knowing%20Doing%20Gap)

![](topics/Concept/Greediness%20in%20Decision%20Making)

![](topics/Concept/Frequency%20Bias)

![](topics/Concept/Exploration%20Techniques)