---
already_read: false
link: https://pair.withgoogle.com/explorables/federated-learning/
read_priority: 1
source: null
type: Content
upload_date: '2022-11-17'
---

https://pair.withgoogle.com/explorables/federated-learning/
## Summary

Federated learning is a machine learning approach that enables collaborative model training using data from multiple users without sharing raw data, thus addressing privacy concerns associated with centralized data collection. It allows devices like smartphones and IoT devices to train models locally and share only model updates, not the data itself. This method can be applied across organizations, such as hospitals and pharmaceutical companies, to improve outcomes while maintaining data privacy.

The process involves local training on user devices, followed by aggregating the updates to create a global model. Techniques like secure aggregation ensure that individual contributions remain confidential. However, challenges arise, such as dealing with outliers and ensuring differential privacy, which prevents the identification of individual users based on their contributions.

Federated learning requires careful balancing of privacy, accuracy, and data volume. While it enhances privacy, it may reduce model accuracy, necessitating trade-offs. The framework is applicable to various domains, including urban mobility and public health, and is supported by tools like TensorFlow Federated for practical implementation.
## Links

1. [TensorFlow Federated](https://www.tensorflow.org/federated) - An open-source framework for implementing federated learning and federated analytics.
2. [Federated Learning: Collaborative Data Science](https://ai.googleblog.com/2020/05/federated-analytics-collaborative-data.html) - A blog post discussing the application of federated learning in collaborative data science.
3. [Differential Privacy in More Detail](https://desfontain.es/privacy/differential-privacy-in-more-detail.html) - A detailed explanation of differential privacy, which is relevant to privacy concerns in federated learning.
4. [Advances and Open Problems in Federated Learning](https://arxiv.org/abs/2108.10241) - A research paper discussing the latest advancements and challenges in the field of federated learning.
5. [Secure Aggregation Protocol](https://queue.acm.org/detail.cfm?id=3501293) - An article detailing the secure aggregation methods used in federated learning to protect user data.
## Topics

![](topics/Concept/Federated%20Learning)

![](topics/Concept/Secure%20Aggregation)

![](topics/Concept/Differential%20Privacy)

![](topics/Library/TensorFlow)

![](topics/Concept/Data%20Minimization)