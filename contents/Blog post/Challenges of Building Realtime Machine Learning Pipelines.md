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

The article discusses the challenges of building real-time machine learning (ML) pipelines, highlighting the trade-offs between performance, cost, and infrastructure complexity. It outlines the transition from batch processing to real-time ML, detailing four stages:

1. **All Batch**: Traditional batch processing is easy to set up but suffers from stale predictions and inefficiencies, making it unsuitable for dynamic environments.

2. **Batch Features with Real-time Models**: This stage introduces real-time model serving while still relying on batch-computed features. Challenges include managing stale features and ensuring reliable model serving.

3. **Real-time Features and Models with Interval Training**: Features and models operate in real-time, improving responsiveness but increasing system complexity and the need for coordination among teams. Monitoring and handling data quality issues become critical.

4. **Fully Real-time Systems with Online Training**: The most complex and costly approach, where models continuously learn in real-time. While powerful, it requires extensive monitoring and can be resource-intensive, often outweighing benefits for many companies.

The article emphasizes the importance of understanding these challenges to mitigate them effectively and suggests that many companies are moving towards more real-time aspects in their ML pipelines for better performance. Third-party tools can help manage the complexities involved.
## Links

1. [7 Reasons Why Realtime ML Is Here To Stay](https://fennel.ai/blog/seven-reasons-why-realtime-ml-is/) - A blog post discussing the benefits and importance of implementing realtime machine learning in modern applications.
2. [Online Offline Feature Skew in Machine Learning](https://fennel.ai/blog/online-offline-feature-skew-in-machine-learning) - An article that explores the challenges of feature skew in machine learning models, particularly in online and offline settings.
3. [FANN: Vector Search in 200 Lines of Rust](https://fennel.ai/blog/fann-vector-search-in-200-lines-of-rust) - A blog post detailing a lightweight implementation of vector search using Rust, relevant for data engineering and machine learning applications.
## Topics

- [[topics/Concept/Realtime Machine Learning Pipelines]]
- [[topics/Concept/Batch Processing]]
- [[topics/Concept/Model Drift Detection]]
- [[topics/Concept/Data Quality Monitoring]]
- [[topics/Library/Fennel]]