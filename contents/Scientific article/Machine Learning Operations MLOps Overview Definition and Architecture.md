---
already_read: false
link: https://arxiv.org/ftp/arxiv/papers/2205/2205.02302.pdf
read_priority: 1
relevance: 0
source: null
tags:
- MlOps
type: Content
upload_date: '2022-12-07'
---

![](artefacts/2205.02302.pdf)
## Summary

The paper provides an overview of Machine Learning Operations (MLOps), highlighting its importance in developing machine learning (ML) products and automating their deployment for production. Key challenges in operationalizing ML projects include manual workflow management and the need for coordination among complex system components. The authors conduct mixed-method research, including literature and tool reviews alongside expert interviews, to derive principles, components, roles, and an architectural framework for MLOps. 

Key Principles identified for effective MLOps practice include Continuous Integration/Continuous Delivery (CI/CD), workflow orchestration, reproducibility, versioning, collaboration, continuous training and evaluation, metadata tracking, continuous monitoring, and feedback loops. 

Essential Components of an MLOps system include CI/CD tools, source code repositories, workflow orchestration tools, feature stores, model training infrastructure, model registries, ML metadata stores, model serving components, and monitoring tools.

Roles necessary for MLOps implementation consist of business stakeholders, solution architects, data scientists, data engineers, software engineers, DevOps engineers, and ML engineers. Each role contributes uniquely to the lifecycle of ML products, from conceptualization through monitoring and governance.

The paper outlines a generalized architectural workflow for implementing MLOps, emphasizing the interplay between various functions and the importance of automation and feedback loops for continuous improvement.

Open challenges in MLOps include cultural shifts in organizations towards a product-focused approach, demand fluctuations during ML training, and operational complexities that require robust automation and governance. The authors define MLOps as an engineering practice that integrates machine learning, software engineering, and data engineering to bridge the gap between development and operations in deploying ML systems effectively.
## Topics

![](topics/Concept/Continuous%20Integration%20and%20Continuous%20Delivery%20CI%20CD)

![](topics/Concept/Workflow%20Orchestration)

![](topics/Tool/Apache%20Airflow)

![](topics/Tool/Kubeflow)

![](topics/Tool/MLflow)

![](topics/Tool/Jenkins)

![](topics/Concept/Model%20Registry)

![](topics/Concept/Continuous%20Monitoring)

![](topics/Tool/Prometheus)

![](topics/Concept/Feedback%20Loops)