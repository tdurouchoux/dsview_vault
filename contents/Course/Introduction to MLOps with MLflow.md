---
already_read: false
link: https://inseefrlab.github.io/formation-mlops/slides/fr/index.html#/title-slide
read_priority: 1
source: null
tags:
- MlOps
type: Content
upload_date: '2023-10-05'
---

https://inseefrlab.github.io/formation-mlops/slides/fr/index.html#/title-slide
## Summary

Le contenu présente une introduction au MLOps avec MLflow, abordant les défis de la mise en production des modèles de machine learning et l'importance d'intégrer les meilleures pratiques du génie logiciel. 

**Principes de MLOps :**
- Reproductibilité
- Contrôle de version
- Automatisation
- Surveillance
- Collaboration

**Pourquoi MLflow ?**
- Open-source et couvre l'ensemble du cycle de vie d'un modèle ML.
- Agnostique au package ML utilisé.

**Plan de la formation :**
1. Introduction à MLFlow
2. Exemple concret : prédiction du code APE
3. Servir un modèle ML à des utilisateurs
4. Maintenance d'un modèle en production
5. Optimisation des hyperparamètres

**Applications pratiques :**
- Utilisation de MLflow pour le suivi des expérimentations et la gestion des modèles.
- Déploiement d'un modèle via une API REST sur Kubernetes.
- Surveillance des modèles en production, intégration de logs et création de tableaux de bord pour l'observabilité.
- Distribution de l'optimisation des hyperparamètres à l'aide d'Argo Workflows.

**Bilan :**
MLflow est polyvalent, facilitant l'utilisation de frameworks personnalisés et l'industrialisation de l'entraînement, bien que des limites subsistent concernant l'accessibilité des modèles entraînés et leur déploiement.
## Links

1. [MLflow](https://datalab.sspcloud.fr/launcher/automation/mlflow?autoLaunch=true) - A platform for managing the machine learning lifecycle, including experimentation, reproducibility, and deployment.
2. [DuckDB](https://duckdb.org/) - A database management system that can be used for querying data, particularly useful for handling parquet files in data science workflows.
3. [Grafana](https://grafana.com/) - An open-source platform for monitoring and observability, useful for creating dashboards to visualize metrics and logs from machine learning models.
4. [Apache Superset](https://superset.apache.org/) - A modern data exploration and visualization platform that can be used to create dashboards and analyze data.
5. [Quarto Dashboards](https://quarto.org/docs/dashboards/) - A framework for creating dashboards and reports, useful for visualizing data and metrics in data science projects.
## Topics

![](topics/Concept/MLOps)

![](topics/Library/MLflow)

![](topics/Platform/Kubernetes)

![](topics/Product/FastAPI)

![](topics/Concept/Hyperparameter%20Optimization)