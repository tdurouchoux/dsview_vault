---
already_read: true
link: https://deepmind.google/discover/blog/facts-grounding-a-new-benchmark-for-evaluating-the-factuality-of-large-language-models/
read_priority: 3
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2024-12-28'
---

https://deepmind.google/discover/blog/facts-grounding-a-new-benchmark-for-evaluating-the-factuality-of-large-language-models/
## Summary

The content introduces FACTS Grounding, a new benchmark developed by Google DeepMind to evaluate the factual accuracy and grounding of large language models (LLMs). The benchmark aims to address the issue of LLMs hallucinating false information, which can erode trust and limit their real-world applications.

Key points include:

1. **FACTS Grounding Dataset**: Comprises 1,719 examples, divided into public and private sets, with documents up to 32,000 tokens covering various domains. The examples focus on tasks like summarization, Q&A, and rewriting, excluding creativity, mathematics, or complex reasoning.

2. **Evaluation Methodology**: Uses three frontier LLM judges (Gemini 1.5 Pro, GPT-4o, and Claude 3.5 Sonnet) to evaluate responses in two phases: eligibility and factual accuracy. The judges ensure responses are grounded in the provided document without hallucinations.

3. **Leaderboard**: Launched on Kaggle to track progress and encourage industry-wide improvement. The leaderboard will be updated as the field advances.

4. **Future Plans**: The benchmark will evolve to keep pace with progress, with the aim of continually raising the bar for factuality and grounding in LLMs.

The initiative is a collaboration between Google DeepMind and Google Research, with contributions from various researchers and acknowledgments to supporting teams.
## Links

- [FACTS Grounding Dataset](http://www.kaggle.com/datasets/deepmind/facts-grounding-examples) : The FACTS Grounding dataset, comprising 1,719 examples, is designed to evaluate the factuality and grounding of large language models (LLMs). It includes diverse documents and user requests across various domains, aiming to assess the models' ability to generate accurate and well-grounded responses.
- [FACTS Leaderboard](http://www.kaggle.com/facts-leaderboard) : The FACTS Leaderboard on Kaggle tracks the performance of leading LLMs using the FACTS Grounding benchmark. It provides a measure of how accurately LLMs ground their responses in provided source material and avoid hallucinations, with scores based on both public and private evaluation sets.

## Topics

![](topics/Concept/FACTS%20Grounding)

![](topics/Dataset/FACTS%20Grounding%20Dataset)

![](topics/Concept/Hallucinations%20in%20LLMs)

![](topics/Concept/LLM%20Judges)