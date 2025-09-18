---
already_read: false
link: https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
read_priority: 1
relevance: 0
source: null
tags:
- MlOps
- Feature_Engineering
type: Content
upload_date: '2023-01-19'
---

https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
## Summary

The post discusses the evolution and importance of feature platforms in machine learning operations (MLOps), focusing on their role in feature engineering, computation, and serving computed features for models. It highlights the benefits of feature platforms, such as reducing engineering time and improving performance, as seen in companies like LinkedIn.

The content is divided into two main parts:

1. **Evolution of Feature Platforms**:
   - **Feature Platform vs. Feature Store**: A feature store is part of a feature platform, focusing on reducing feature retrieval latency and storing computed features for reuse. Feature platforms handle both feature retrieval and computation.
   - **Feature Platform vs. Model Platform**: Feature platforms concern the entire feature engineering workflow, while model platforms focus on model packaging and serving.
   - **Types of Features**: Feature platforms can compute batch, real-time (RT), and near real-time (NRT) features, each with different latency and use cases.

2. **Self-Serve Feature Engineering**:
   - **Challenge**: Slow iteration speed for streaming features.
   - **Feature API**: Discusses different interfaces (Scala, SQL, Python) and considerations for feature APIs, including one-off batch computation vs. ongoing stream computation and the separation of transformation logic and feature logic.
   - **Functionality for Fast Experimentation**: Highlights the importance of data discoverability, governance, and automated backfills for speeding up iteration for streaming features.

The post also includes a comparison of feature platforms from various companies, a list of reference feature platforms, and a conclusion emphasizing the importance of speed in feature platforms and the challenges of building them. It concludes with an appendix detailing the differences between batch, real-time, and near real-time features.
## Links

- [Feathr GitHub Repository](https://github.com/feathr-ai/feathr) : The GitHub repository for Feathr, LinkedIn's feature store for productive machine learning.
- [Binance Machine Learning Feature Store](https://www.binance.com/en/blog/all/a-closer-look-at-our-machine-learning-feature-store-3411614684128221181) : An in-depth look at Binance's machine learning feature store, detailing its architecture and implementation.
- [Pinterest Big Data Machine Learning Platform](https://www.slideshare.net/Alluxio/pinterest-big-data-machine-learning-platform-at-pinterest?ref=http://featurestore.org/) : A presentation on Pinterest's big data machine learning platform, covering its architecture and use cases.

## Topics

![[topics/Concept/Data Discoverability and Governance]]

![[topics/Concept/Batch Features]]

![[topics/Concept/Automated Backfills]]

![[topics/Concept/Real time Features]]

![[topics/Concept/Model Platform]]

![[topics/Concept/Feature Platform]]

![[topics/Concept/Feature Store]]

![[topics/Concept/Feature API]]

![[topics/Concept/Near Real time Features]]