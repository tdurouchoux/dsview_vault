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

Probabilistic Principal Components Analysis (PPCA) is a dimensionality reduction technique that uses a latent variable framework to find directions of maximal variance in data. It is closely related to classical PCA when noise follows an Isotropic Gaussian distribution, differing only by a scaling factor and orthogonal rotation. PPCA can handle missing data, unlike classical PCA.

PPCA can be implemented using the EM algorithm. The EM algorithm iteratively estimates latent variables and updates parameters. For incomplete data, the algorithm is extended to compute expectations of missing values and update parameters accordingly. The algorithm converges to local maximum likelihood estimators.

A Python implementation of the EM algorithm for PPCA is provided, which can handle missing data. Simulations show that the algorithm performs well even with missing values, demonstrating robustness to non-random patterns of missingness.

In conclusion, PPCA extends the functionality of classical PCA by accommodating missing data and providing accurate parameter estimates. The EM algorithm for PPCA is effective in handling incomplete data, making it a valuable tool for dimensionality reduction in various applications.
## Links

- [PPCA Python Implementation](https://github.com/nstew296/ppca/blob/main/test_ppca.py) : Python implementation of the EM algorithm for PPCA, accommodating missing data.
- [Probabilistic View of Principal Component Analysis](https://towardsdatascience.com/probabilistic-view-of-principal-component-analysis-9c1bbb3f167) : An article discussing the probabilistic view of principal component analysis, providing insights into the relationship between PPCA and classical PCA.

## Topics

![](topics/Concept/Latent%20Variable)

![](topics/Concept/Probabilistic%20Principal%20Components%20Analysis%20PPCA)

![](topics/Concept/Expectation%20Maximization%20EM%20Algorithm)

![](topics/Concept/Isotropic%20Gaussian%20Distribution)

![](topics/Model/Principal%20Components%20Analysis%20PCA)