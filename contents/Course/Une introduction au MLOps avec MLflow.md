---
already_read: false
link: https://inseefrlab.github.io/formation-mlops/slides/fr/index.html
read_priority: 1
relevance: 0
source: null
tags:
- MlOps
type: Content
upload_date: '2023-10-05'
---

https://inseefrlab.github.io/formation-mlops/slides/fr/index.html
## Summary

Le document présente une introduction au MLOps en utilisant MLflow, un outil open-source pour gérer le cycle de vie des modèles de machine learning. Les auteurs, Romain Avouac, Thomas Faria, et Tom Seimandi de l'Insee, soulignent les défis de transition de l'expérimentation à la production des modèles et l'importance d'adopter des pratiques de génie logiciel pour améliorer la reproductibilité, le déploiement et la surveillance des applications.

L'approche MLOps allie les principes de DevOps, en intégrant des aspects spécifiques au machine learning, tels que l'expérimentation et l'amélioration continue. Les principes fondamentaux du MLOps incluent la reproductibilité, le contrôle de version, l'automatisation, la surveillance, et la collaboration.

MLflow se distingue par sa capacité à couvrir l'ensemble du cycle de vie d'un modèle, indépendamment du framework utilisé. Le document décrit plusieurs applications pratiques, intégrant des exemples concrets comme la prédiction de codes APE avec un modèle FastText, ainsi que des étapes pour déployer un modèle via une API REST sur Kubernetes.

D'autres sections portent sur la maintenance des modèles en production, le suivi des performances (data drift, concept drift), et la mise en place de workflows automatisés pour l'optimisation des hyperparamètres grâce à Argo Workflows. Les conclusions soulignent la nécessité d'une communication efficace entre les équipes impliquées pour superviser les modèles en production et améliorer continuellement les processus. 

En résumé, MLflow permet une gestion efficace des modèles ML, avec une attention particulière portée à la reproductibilité et à la collaboration au sein des équipes de data science.
## Links

- [MLflow - Open Source Platform for Managing the ML Lifecycle](https://mlflow.org/) : An overview of MLflow, including managing the lifecycle of machine learning projects.
- [DuckDB - The Fastest SQL OLAP Database](https://duckdb.org/) : DuckDB is an in-process SQL OLAP database management system for analytics workloads.
- [Grafana - Open Source Analytics & Monitoring Solution](https://grafana.com/) : Grafana provides visualization and analytics for monitoring data.
- [Apache Superset - Modern Data Exploration and Visualization Platform](https://superset.apache.org/) : Superset is a data exploration and visualization platform designed to be easy to use.
- [Quarto - Scientific and Technical Publishing System](https://quarto.org/docs/dashboards/) : Quarto is a system for publishing research or technical documents and dashboards.

## Topics

![](topics/Platform/MLflow)

![](topics/Concept/Hyperparameter%20Optimization)

![](topics/Library/FastAPI)

![](topics/Concept/Continuous%20Deployment)

![](topics/Library/Docker)

![](topics/Platform/Kubernetes)

![](topics/Concept/Data%20Drift%20Monitoring)

![](topics/Platform/ArgoCD)

![](topics/Concept/ETL%20Extract%20Transform%20Load)

![](topics/Library/DuckDB)