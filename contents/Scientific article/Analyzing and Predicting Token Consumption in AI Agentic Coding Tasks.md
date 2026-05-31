---
already_read: true
link: https://arxiv.org/pdf/2604.22750
read_priority: 0
relevance: 4
source: null
tags:
- Large_Language_Model
type: Content
upload_date: '2026-05-31'
---

https://arxiv.org/pdf/2604.22750
## Summary

Agentic coding tasks consume **1000–3500x more tokens** than single-turn code reasoning or chat, primarily due to **input token accumulation** (even with caching). Key findings:

- **High variability**: Token usage varies up to **30x** across runs on the same task; higher cost doesn’t guarantee better accuracy (performance peaks at intermediate costs).
- **Model inefficiency**: Kimi-K2 and Claude-Sonnet-4.5 consume **1.5M+ more tokens** than GPT-5 on identical tasks.
- **Human vs. model complexity**: Expert-rated task difficulty weakly predicts actual token costs (Kendall τb = 0.32).
- **Prediction failure**: Models poorly estimate their own token usage (max correlation: **0.39**), systematically **underestimating costs** (especially input tokens).

**Cost drivers**: Cache-read input tokens dominate expenses across all phases, with spikes from tool calls (e.g., file views, test execution). **Action redundancy** (repeated file edits/views) inflates costs without improving outcomes.

**Implications**: Current pricing models lack transparency; pre-execution cost prediction remains an unsolved challenge despite attempts at self-prediction. Efficiency gaps stem from model-specific behaviors rather than task difficulty.
## Links


## Topics

![[topics/Concept/Token Consumption in AI Agents]]

![[topics/Concept/Agentic Coding]]

![[topics/Concept/Token Efficiency in Models]]

![[topics/Concept/Pre Execution Token Consumption Prediction]]

![[topics/Concept/Cache Aware Token Pricing]]

![[topics/Concept/Inverse Test Time Scaling]]

![[topics/Tool/OpenHands]]

![[topics/Concept/SWE bench Verified]]