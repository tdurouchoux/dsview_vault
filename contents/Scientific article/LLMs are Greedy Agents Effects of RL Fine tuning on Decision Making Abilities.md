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

![](artefacts/2504.16078)
## Summary

This study investigates the decision-making capabilities of Large Language Models (LLMs) in agentic applications, focusing on the hypothesis that LLMs can leverage common sense and Chain-of-Thought (CoT) reasoning to perform effectively in complex environments. However, the authors identify three failure modes: greediness, frequency bias, and the knowing-doing gap, which hinder LLMs' performance in decision-making tasks.

To address these shortcomings, the authors propose fine-tuning LLMs with Reinforcement Learning (RL) using self-generated CoT rationales, which enhances decision-making abilities by improving exploration and reducing the knowing-doing gap. Experiments were conducted using settings like multi-armed bandits and Tic-tac-toe, demonstrating that RL fine-tuning (RLFT) significantly improves performance over baseline methods by decreasing cumulative regret while encouraging broader action coverage.

Techniques evaluated include classic exploration strategies (like ε-greedy) and LLM-specific methods (self-correction, self-consistency), showing that structured exploration can help address the identified failure modes while highlighting the importance of reward shaping in fine-tuning processes.

Key contributions of the work include:
- A systematic analysis of failure modes impacting LLMs in decision-making.
- Demonstration of the effectiveness of RL fine-tuning on self-generated CoT rationales.
- Evaluation of various exploration mechanisms to mitigate sub-optimal behavior in LLMs.

Future research is suggested to explore the application of these findings to larger-scale models and more complex environments requiring focused exploration strategies.
## Topics

![](topics/Concept/Reinforcement%20Learning%20Fine%20Tuning%20RLFT)

![](topics/Concept/Greediness%20in%20Decision%20Making)

![](topics/Concept/Frequency%20Bias)

![](topics/Concept/Knowing%20Doing%20Gap)

![](topics/Concept/Chain%20of%20Thought%20Reasoning)

![](topics/Model/Gemma)

![](topics/Concept/Exploration%20Strategies)

![](topics/Concept/Expert%20Behavior%20Cloning%20vs%20Thought%20Cloning)