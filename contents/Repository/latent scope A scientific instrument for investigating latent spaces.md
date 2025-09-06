---
already_read: false
link: https://github.com/enjalot/latent-scope
read_priority: 1
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2024-02-22'
---

https://github.com/enjalot/latent-scope
## Summary

Latent Scope is a tool designed for visualizing and exploring datasets through latent spaces. It encodes a common AI and data science workflow: embedding unstructured data into high-dimensional vectors, reducing dimensionality, clustering, labeling clusters with an LLM, and exploring the annotated data. The tool provides a web interface for each step and an interactive visualization tightly coupled with the input data.

Key features include:
- **Quick Start**: Works on Mac, Linux, and Windows with Python 3.12. Installation and setup are straightforward via command line.
- **Python Interface**: Allows data ingestion from a Pandas dataframe.
- **Command Line Scripts**: Detailed scripts for each step of the process, from ingesting data to serving the web interface.
- **Design Principles**: Emphasizes ease of data input and output, recording all choices made during the process, and using indices into the input dataset for all operations.
- **Dataset Directory Structure**: Organizes data and metadata in flat files for easy export and use in other pipelines.

Example analyses include exploring survey responses, clustering GitHub issues and PRs, and exploring US Federal laws. The tool supports several open-source embedding models and proprietary API services, with plans to make adding new models and services quick and easy.
## Links

- [Latent Scope Documentation](https://enjalot.github.io/latent-scope/install-and-config) : Documentation for Latent Scope, providing guides on installation, configuration, and usage.
- [Latent Scope Demo - DataVis Survey](https://enjalot.github.io/latent-scope/datavis-survey) : A demo showcasing the analysis of a DataVis survey using Latent Scope.
- [Latent Scope Demo - US Federal Laws](https://enjalot.github.io/latent-scope/us-federal-laws) : A demo exploring 50,000 US Federal laws spanning two hundred years using Latent Scope.
- [Latent Scope PyPI](https://pypi.org/project/latentscope/) : The PyPI page for Latent Scope, providing installation and usage information for the Python package.

## Topics

![](topics/Tool/Latent%20Scope)

![](topics/Concept/Latent%20Spaces)

![](topics/Concept/UMAP%20Uniform%20Manifold%20Approximation%20and%20Projection)

![](topics/Concept/HDBSCAN)

![](topics/Concept/Embedding%20Models)