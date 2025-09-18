---
already_read: false
link: https://pair.withgoogle.com/explorables/federated-learning/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Analysis
type: Content
upload_date: '2022-11-17'
---

https://pair.withgoogle.com/explorables/federated-learning/
## Summary

Federated learning is a privacy-preserving machine learning approach that enables collaborative model training without sharing raw data. It's particularly useful when data is personal or proprietary, allowing multiple entities to improve a global model while keeping their data local.

Key points:

1. **Privacy Preservation**: Federated learning allows model training without sharing raw data, addressing privacy concerns and barriers to centralized data collection.

2. **System Design**: The process involves local model training on individual devices, followed by secure aggregation of these models on a central server. Secure aggregation ensures that individual contributions remain private.

3. **Challenges and Solutions**:
   - **Outliers**: Detecting and handling outliers is challenging due to the lack of direct access to user data. Techniques like differential privacy can help mitigate the impact of outliers.
   - **Differential Privacy**: This technique adds noise to the training process to prevent the global model from being significantly influenced by any single user's data, enhancing privacy.

4. **Trade-offs**: There's a trade-off between privacy, accuracy, and the amount of data. More data can improve accuracy but also increases computational costs.

5. **Applications**: Federated learning can be applied across various domains, such as healthcare, autonomous vehicles, and urban mobility, enabling large-scale aggregation and modeling of complex systems.

6. **Tools and Resources**: TensorFlow Federated is an open-source framework for implementing federated learning, and there are various resources available for further learning and experimentation.

The content also highlights the importance of considering fairness and personalization in federated learning models to ensure they perform well for all users.
## Links

- [Federated Learning: Collaborative Machine Learning without Centralized Training Data](http://ai.googleblog.com/2017/04/federated-learning-collaborative.html) : This link is to a blog post introducing the concept of federated learning, a machine learning technique that enables multiple entities to collaboratively train a model while keeping all the training data on local devices. The post explains the benefits of federated learning, such as improved privacy and reduced data transfer, and provides an example of how it can be used to build a keyboard prediction model.
- [Advances and Open Problems in Federated Learning](https://arxiv.org/abs/1905.10497) : This link is to a research paper that provides an overview of the current state of federated learning, including its applications, challenges, and open research questions. The paper covers topics such as secure aggregation, personalized federated learning, and federated reinforcement learning.
- [Federated Learning with Formal Privacy Guarantees](https://ai.googleblog.com/2022/02/federated-learning-with-formal.html) : This link is to a blog post that discusses how to provide formal privacy guarantees in federated learning. The post explains the concept of differential privacy and how it can be applied to federated learning to ensure that the privacy of individual users is protected.

## Topics

![[topics/Concept/Secure Aggregation]]

![[topics/Concept/Confidentialité différentielle]]

![[topics/Concept/Federated Learning]]