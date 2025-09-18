---
already_read: false
link: https://blog.lmarena.ai/blog/2025/search-arena/
read_priority: 3
relevance: 0
source: Data Points
tags:
- Large_Language_Model
type: Content
upload_date: '2025-04-21'
---

https://blog.lmarena.ai/blog/2025/search-arena/
## Summary

The document introduces Search Arena, a crowdsourced evaluation platform for search-augmented LLM systems based on human preference. Key points include:

1. **Purpose and Data**: Search Arena focuses on current events and diverse real-world use cases, unlike static benchmarks. It has collected over 7k human votes, with Gemini-2.5-Pro-Grounding and Perplexity-Sonar-Reasoning-Pro leading the rankings.

2. **Features Correlated with Human Preference**: Response length, citation count, and citing specific web sources like YouTube and online forums/blogs show strong positive correlation with user preference.

3. **Citation Style Analysis**: Standardizing citation styles had minimal effect on model rankings, though it positively impacted individual model scores.

4. **Model Performance**: The leaderboard highlights the top-performing models and analyzes the impact of different features like response length, citation count, and source domains on user preferences.

5. **Future Directions**: The platform aims to expand participation, evaluate cross-task performance, and improve open models.

The dataset and analysis code have been open-sourced for further exploration and contributions.
## Links

- [Search Arena Dataset](https://huggingface.co/datasets/lmarena-ai/search-arena-v1-7k) : The dataset used for the Search Arena evaluation, containing 7k human votes on search-augmented LLM systems.
- [Colab Notebook for Leaderboard Analysis](https://colab.research.google.com/drive/1h7rR7rhePBPuIfaWsVNlW87kv3DLibPS?usp=sharing) : A Colab notebook for analyzing the leaderboard data from Search Arena.

## Topics

![[topics/Concept/Citation Style]]

![[topics/Concept/Citation Count]]

![[topics/Concept/Search Augmented LLM Systems]]

![[topics/Concept/Human Preference]]

![[topics/Concept/Crowdsourced Evaluation]]

![[topics/Concept/Bradley Terry Model]]

![[topics/Concept/Response Length]]