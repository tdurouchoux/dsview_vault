---
already_read: false
link: https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
read_priority: 1
relevance: 0
source: null
tags:
- Feature_Engineering
type: Content
upload_date: '2023-01-19'
---

https://huyenchip.com/2023/01/08/self-serve-feature-platforms.html
## Summary

The article discusses self-serve feature platforms, focusing on their architectures, APIs, and the evolution of feature platforms within the MLOps stack. 

**Part I: Evolution of Feature Platforms**
- **Definition and Distinction**: Feature platforms enable feature engineering, computation, and serving for model predictions. They differ from feature stores (which primarily store computed features) and model platforms (which handle model packaging and serving).
- **Latency Types**: Key latency issues include feature computation, retrieval, and prediction computation latencies.
- **Feature Types**: Companies usually need platforms that can handle batch, real-time, and near-real-time features for varied data ingestion and computation based on business needs.

**Part II: Self-Serve Feature Engineering**
- **Challenges**: Data scientists face slow iteration for streaming features, often preferring batch features instead.
- **Feature APIs**: There’s a need for user-friendly APIs; the article discusses the adoption of Scala, SQL, and Python for feature APIs, highlighting Python's growing popularity.
- **Functionality**: Fast experimentation is hindered by insufficient data discoverability and governance. Key features include automated backfills for historical value generation to facilitate local experimentation before deployment.

**Key Takeaways**:
- Building a feature platform is complex and requires serious investment; it often involves trial and error.
- A well-designed feature platform enhances ML model iteration and prediction capabilities.
- Established companies need to continuously adapt and innovate around their feature platforms to remain efficient and effective in ML deployments.
## Links

- [Building a Declarative Real-Time Feature Engineering Framework at DoorDash](https://doordash.engineering/2021/03/04/building-a-declarative-real-time-feature-engineering-framework/) : An overview of the feature engineering framework developed by DoorDash, focusing on real-time features.
- [Using MLOps to Build a Real-Time End-to-End Machine Learning Pipeline on Binance](https://binance.com/en/blog/all/using-mlops-to-build-a-realtime-endtoend-machine-learning-pipeline-3820048062346322706) : A discussion on how Binance utilizes MLOps for real-time machine learning pipelines.
- [Lessons Learned: The Journey to Real-Time Machine Learning at Instacart](https://tech.instacart.com/lessons-learned-the-journey-to-real-time-machine-learning-at-instacart-942f3a656af3) : Insights into Instacart's transition from batch to real-time machine learning, highlighting key strategies and lessons learned.
- [Open Sourcing Feathr: LinkedIn’s Feature Store for Productive Machine Learning](https://engineering.linkedin.com/blog/2022/open-sourcing-feathr---linkedin-s-feature-store-for-productive-m) : A detailed look at LinkedIn's Feathr, an open-source feature store designed to improve machine learning productivity.
- [Speed Up Feature Engineering at Snap](https://eng.snap.com/speed-up-feature-engineering) : A presentation on how Snap has optimized feature engineering processes to enhance ML model performance.

## Topics

![](topics/Platform/Feature%20Platform)

![](topics/Concept/Feature%20Store)

![](topics/Concept/Real%20Time%20and%20Near%20Real%20Time%20Features)

![](topics/Tool/Flink)

![](topics/Tool/Spark)

![](topics/Concept/Feature%20API)

![](topics/Tool/Feature%20Engineering%20Tools)