---
already_read: false
link: https://fennel.ai/blog/challenges-of-building-realtime-ml-pipelines/
read_priority: 1
source: null
tags:
- MlOps
type: Content
upload_date: '2022-12-07'
---

https://fennel.ai/blog/challenges-of-building-realtime-ml-pipelines/
## Summary

The article discusses the challenges of building real-time machine learning (ML) pipelines, highlighting the trade-offs between performance, cost, and infrastructure complexity. It outlines the transition from batch processing to real-time ML, detailing four stages of implementation:

1. **All Batch**: Traditional batch processing is easy to set up but suffers from stale predictions and inefficiencies, making it unsuitable for dynamic environments.

2. **Batch Features with Real-time Models**: This stage introduces real-time model serving while still relying on batch-computed features. It improves accuracy but requires careful monitoring and can struggle with personalization and rapid response needs.

3. **Real-time Features and Models with Interval Training**: Features and models operate in real-time, allowing for immediate responses to data changes. However, this increases system complexity and necessitates robust monitoring and coordination among teams.

4. **Fully Real-time Systems with Online Training**: The most complex and costly approach, where models continuously learn in real-time. While powerful, it demands extensive resources and monitoring to manage potential issues with data quality and model performance.

The article emphasizes the importance of understanding these challenges to effectively implement real-time ML pipelines and suggests that many companies are moving towards real-time solutions for their performance benefits, often with the aid of third-party tools to mitigate complexity.
## Links

1. [7 Reasons Why Realtime ML Is Here To Stay](https://fennel.ai/blog/seven-reasons-why-realtime-ml-is/) - A blog post discussing the advantages of implementing realtime machine learning in business applications.
2. [Fennel AI GitHub](https://github.com/fennel-ai) - The GitHub repository for Fennel AI, which may contain relevant tools and resources for building ML pipelines.
3. [Online Offline Feature Skew in Machine Learning](https://fennel.ai/blog/online-offline-feature-skew-in-machine-learning) - An article that explores the challenges of feature skew in machine learning, relevant to the discussion of realtime ML pipelines.
## Topics

![](topics/Concept/Realtime%20Machine%20Learning%20Pipelines)

![](topics/Product/Fennel)

![](topics/Concept/Batch%20Processing)

![](topics/Concept/Model%20Drift%20Detection)

![](topics/Concept/Online%20Model%20Training)