---
already_read: false
link: https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
read_priority: 1
source: null
tags:
- MlOps
- Feature_Engineering
type: Content
upload_date: '2023-01-19'
---

https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
## Summary

The content discusses the evolution and architecture of self-serve feature platforms, which are essential for efficient machine learning (ML) workflows. It is divided into two main parts.

Part I covers the evolution of feature platforms, differentiating them from feature stores and model platforms. Feature platforms facilitate feature engineering, computation, and serving, crucial for online predictions. They address latency issues related to feature computation, retrieval, and prediction. Feature stores are a subset of feature platforms focused on storing and retrieving computed features, while model platforms manage model deployment and serving.

Key types of features include batch, real-time (RT), and near real-time (NRT) features, each requiring different computation methods and engines. The need for feature platforms has grown as companies transition from batch to online predictions, necessitating rapid iteration and collaboration between data scientists and engineers.

Part II focuses on self-serve feature engineering, highlighting challenges like slow iteration speeds for streaming features. It emphasizes the importance of user-friendly APIs (Scala, SQL, Python) and functionalities for fast experimentation, such as data discoverability, governance, and automated backfills. The section also compares various feature platforms used by companies like LinkedIn, Airbnb, and DoorDash.

The conclusion stresses that while building a feature platform can be resource-intensive, it significantly enhances the speed of data utilization and model improvement. As technology matures, the process of developing these platforms is expected to become more efficient.
## Links

1. [Open sourcing Feathr – LinkedIn’s feature store for productive machine learning](https://engineering.linkedin.com/blog/2022/open-sourcing-feathr---linkedin-s-feature-store-for-productive-m) - A detailed overview of LinkedIn's feature store, Feathr, and its capabilities for enhancing machine learning workflows.
2. [Building a Declarative Real-Time Feature Engineering Framework](https://doordash.engineering/2021/03/04/building-a-declarative-real-time-feature-engineering-framework/) - Insights into DoorDash's approach to building a feature engineering framework that supports real-time data processing.
3. [Lessons Learned: The Journey to Real-Time Machine Learning at Instacart](https://tech.instacart.com/lessons-learned-the-journey-to-real-time-machine-learning-at-instacart-942f3a656af3) - A case study on Instacart's transition to real-time machine learning and the challenges faced during the process.
4. [Speed Up Feature Engineering for Recommendation Systems](https://eng.snap.com/speed-up-feature-engineering) - An exploration of techniques and strategies used by Snap to enhance feature engineering for their recommendation systems.
5. [Using MLOps to Build a Real-time End-to-End Machine Learning Pipeline](https://binance.com/en/blog/all/using-mlops-to-build-a-realtime-endtoend-machine-learning-pipeline-3820048062346322706) - A discussion on how Binance implemented MLOps practices to create a real-time machine learning pipeline.
## Topics

![](topics/Concept/Feature%20Store%20and%20Feature%20Platform)

![](topics/Product/Feathr)

![](topics/Product/Chronon)

![](topics/Product/Flink)

![](topics/Product/Spark)