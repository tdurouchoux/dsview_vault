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

Google DeepMind has introduced FACTS Grounding, a benchmark designed to assess the factual accuracy of large language models (LLMs). This new tool addresses the issue of LLMs sometimes generating incorrect information or "hallucinations," which undermines their reliability. The benchmark includes an online leaderboard to monitor LLM performance in terms of how well they ground their responses in provided source material.

Key features of FACTS Grounding include:

1. **Dataset Composition**: The benchmark utilizes a dataset of 1,719 examples that require long-form responses based on specific documents. This dataset is split into public (860) and private (859) sets to ensure integrity against contamination.

2. **Diverse Inputs**: The examples cover various domains and request types, avoiding tasks that could require advanced reasoning or creativity.

3. **Evaluation Methodology**: Responses are judged based on eligibility (addressing the user’s request) and factual accuracy (grounded in the provided information). Three different LLM judges are used to minimize bias.

4. **Continuous Improvement**: Recognizing that benchmarks can quickly become outdated, FACTS Grounding will evolve to maintain relevance and effectiveness, aiming to enhance the accuracy and reliability of future LLMs.

The initiative is a collaborative effort within the Google DeepMind and Google Research teams, emphasizing the significance of increasing accountability and trust in AI technologies.
## Links

- [FACTS Leaderboard on Kaggle](http://www.kaggle.com/facts-leaderboard) : Access the FACTS leaderboard to track the performance of large language models in grounding and factual accuracy.
- [FACTS Grounding Dataset on Kaggle](http://www.kaggle.com/datasets/deepmind/facts-grounding-examples) : Explore the FACTS Grounding dataset, which contains examples for evaluating LLMs on factuality.
- [GitHub for Google DeepMind](https://github.com/google-deepmind) : View the repositories related to the research and technologies developed by Google DeepMind.
- [FACTS Paper](https://goo.gle/FACTS_paper) : Access the academic paper detailing the FACTS Grounding methodology and findings.
- [Gemini AI Model Overview](https://gemini.google.com/?utm_source=deepmind.google&utm_medium=referral&utm_campaign=gdm&utm_content=) : Learn more about Gemini, a sophisticated AI model developed by Google DeepMind.

## Topics

![](topics/Concept/Factuality%20in%20AI)

![](topics/Dataset/FACTS%20Grounding%20Dataset)

![](topics/Platform/Kaggle)

![](topics/Concept/Model%20Evaluation%20Methodology)