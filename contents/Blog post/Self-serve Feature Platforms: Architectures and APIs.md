---
already_read: false
link: https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
read_priority: 1
source: null
tags:
- MlOps
type: Content
upload_date: '2023-01-19'
---

https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
## Summary

Self-serve feature platforms have emerged as a crucial component of the MLOps stack, enhancing machine learning production workflows by managing feature engineering, computation, and serving. The evolution of feature platforms is discussed, highlighting their distinction from feature stores and model platforms. Feature platforms optimize feature computation and retrieval, addressing latency issues critical for online predictions.

Key challenges in making feature platforms self-serve for data scientists include slow iteration speeds for streaming features. The post outlines the need for user-friendly APIs and functionalities that facilitate rapid experimentation. Various feature APIs are explored, including Scala, SQL, and Python interfaces, with a focus on their pros and cons.

The article categorizes feature types into batch, real-time, and near real-time features, each requiring different computation methods and engines. It emphasizes the importance of data discoverability, governance, and automated backfills for efficient feature engineering.

The conclusion stresses that while building a feature platform can be resource-intensive, it significantly enhances the speed of data utilization for improving ML predictions and iteration speed for data scientists. The process of developing these platforms is complex and often involves trial and error, but advancements in technology are expected to simplify future implementations.
## Links

1. [Feathr](https://engineering.linkedin.com/blog/2022/open-sourcing-feathr---linkedin-s-feature-store-for-productive-m) - LinkedIn's open-source feature store designed to enhance productivity in machine learning.
2. [Lessons Learned: The Journey to Real-Time Machine Learning at Instacart](https://tech.instacart.com/lessons-learned-the-journey-to-real-time-machine-learning-at-instacart-942f3a656af3) - Insights from Instacart on transitioning to real-time machine learning.
3. [Introduction to streaming for data scientists](https://huyenchip.com/2022/08/03/stream-processing-for-data-scientists.html#time-travel-backfilling) - A guide on streaming concepts tailored for data scientists, including backfilling techniques.
4. [Building Riviera: A Declarative Real-Time Feature Engineering Framework](https://doordash.engineering/2021/03/04/building-a-declarative-real-time-feature-engineering-framework/) - Overview of DoorDash's framework for real-time feature engineering.
5. [Chronon - Airbnb’s Feature Engineering Framework](https://microsites.databricks.com/sites/default/files/2022-07/Introducing-Zipline_An-Open-Source-Feature-Engineering-Platform.pdf) - A detailed look at Airbnb's feature engineering framework, which evolved from Zipline.
## Topics

- [[topics/Concept/Feature Platforms]]
- [[topics/Library/Feathr]]
- [[topics/Concept/Feature Store]]
- [[topics/Concept/Feature API]]
- [[topics/Concept/Streaming and Streaming Features]]