---
already_read: true
link: https://hamel.dev/blog/posts/revenge/
read_priority: 0
relevance: 2
source: Data Elixir
tags:
- Large_Language_Model
type: Content
upload_date: '2026-04-26'
---

https://hamel.dev/blog/posts/revenge/
## Summary

The blog post argues that while the role of data scientists has evolved with the rise of LLMs and foundation-model APIs, their core skills remain critical. The author contends that data science is not in decline but has shifted from model training to building evaluation harnesses, designing metrics, and ensuring robust experimental design. Key pitfalls in modern AI systems include relying on generic metrics, unverified judges (LLM-as-a-judge without validation), poor experimental design (e.g., synthetic data not grounded in real production logs), and neglecting data quality and labeling. The post emphasizes the importance of exploratory data analysis, skepticism toward data/labels, and human-in-the-loop processes (e.g., domain experts labeling data). Automation should support—not replace—these human-centric tasks. The overarching message: data science fundamentals (EDA, evaluation, experimental design) are timeless, and Python remains the best tool for these tasks. The author also highlights common mistakes like misusing similarity scores, lack of confidence intervals, and ignoring data drift. The "Mapping" section ties all pitfalls to core data science principles (e.g., trace analysis = EDA, judge validation = model evaluation). The post concludes with a call to action: always look at the data.
## Links

- [Harness Engineering by OpenAI](https://openai.com/index/harness-engineering/) : OpenAI's blog post on harness engineering, discussing how autonomous AI systems like Codex operate within a framework of tests, specifications, and observability stacks (metrics, logs, and traces). Highly relevant to the role of data science in designing and managing such harnesses.
- [Auto-Research Project by Andrej Karpathy](https://x.com/karpathy/status/1936185694238064845) : A tweet by Andrej Karpathy discussing his auto-research project, where models iteratively optimize against validation loss metrics. Supports the content's argument about the importance of metrics and iterative evaluation in AI systems.
- [Criteria Drift Paper by Shreya Shankar et al.](https://arxiv.org/abs/2404.12272) : A research paper titled 'Criteria Drift' by Shreya Shankar and colleagues, exploring how users refine their criteria for evaluating outputs based on seeing LLM-generated results. Relevant to labeling, data collection, and iterative evaluation in AI systems.
- [Evals Skills Plugin by Hamel Husain](https://github.com/hamelsmu/evals-skills) : An open-source plugin created by Hamel Husain that analyzes eval pipelines to identify potential issues or areas for improvement. Directly relevant to the content's focus on eval pitfalls and robust evaluation practices in data science and AI.

## Topics

![[topics/Concept/AI Evaluation]]

![[topics/Concept/Observability in AI Systems]]

![[topics/Concept/Human in the Loop]]

![[topics/Concept/Criteria Drift]]

![[topics/Concept/Exploratory Data Analysis EDA]]

![[topics/Concept/ML Model Monitoring]]

![[topics/Tool/Custom Trace Viewers]]

![[topics/Concept/Synthetic Data Generation]]