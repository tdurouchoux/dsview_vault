---
already_read: false
link: https://readmedium.com/principal-components-analysis-pca-through-a-latent-variable-lens-2c2e5392a3a0
read_priority: 1
relevance: 0
source: null
tags:
- Dimensionality_reduction
- Data_Analysis
type: Content
upload_date: '2024-07-10'
---

https://readmedium.com/principal-components-analysis-pca-through-a-latent-variable-lens-2c2e5392a3a0
## Summary

Probabilistic Principal Components Analysis (PPCA) is a dimensionality reduction technique that uses a latent variable framework to find the directions of maximum variance in data, similar to classical PCA. PPCA assumes a probabilistic model with latent variables, a loading matrix, a mean vector, and a noise term. When noise follows an isotropic Gaussian distribution, PPCA's principal components are closely related to classical PCA's, differing only by scaling and orthogonal rotation.

PPCA can handle incomplete data, unlike classical PCA, by using the Expectation-Maximization (EM) algorithm. The EM algorithm iteratively estimates latent variables and updates parameters, converging to local maximum likelihood estimators. The algorithm can be extended to accommodate missing data by treating missing values as additional latent variables and computing their expectations.

The author provides a Python implementation of the EM algorithm for PPCA, which can handle missing data. Simulations demonstrate the algorithm's accuracy in estimating parameters, even with non-random missingness. PPCA extends classical PCA's functionality, making it useful for data visualization, feature extraction, and handling incomplete data.
## Links

- [PPCA Implementation on GitHub](https://github.com/nstew296/ppca) : GitHub repository containing the implementation of the EM algorithm for PPCA.
- [PPCA Test Code on GitHub](https://github.com/nstew296/ppca/blob/main/test_ppca.py) : GitHub repository containing the test code for the PPCA implementation.

## Topics

![](topics/Concept/Probabilistic%20Principal%20Components%20Analysis%20PPCA)

![](topics/Concept/Latent%20Variable)

![](topics/Concept/Expectation%20Maximization%20EM%20Algorithm)

![](topics/Concept/Isotropic%20Gaussian%20Distribution)

![](topics/Model/Principal%20Components%20Analysis%20PCA)