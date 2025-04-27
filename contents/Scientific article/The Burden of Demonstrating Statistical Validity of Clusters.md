---
already_read: true
link: https://www.fharrell.com/post/cluster/
read_priority: 3
relevance: 0
source: Data science weekly
tags:
- Statistics
- Data_Analysis
type: Content
upload_date: '2024-10-12'
---

https://www.fharrell.com/post/cluster/
## Summary

The article discusses the challenges and considerations in demonstrating statistical validity when clustering patients in medical research, particularly for discovering new phenotypes. Key points include:

1. **Clustering Misuse**: Many clustering applications do not align with clinical goals and lack validation, leading to potentially misleading results, as highlighted in critiques of diabetes subtype claims.

2. **Importance of Objective**: Researchers should clarify the goal of clustering—whether it serves for patient classification or outcome prediction—favoring variable clustering over patient clustering to preserve information and manage redundancies.

3. **Presentation of Results**: Instead of binary cluster classification, which can misrepresent data, results should be presented as continuous variables that quantify patient distances to cluster centers or cluster membership probabilities.

4. **Validation of Cluster Membership**: Forced-choice classifications require verification of compact condition and should be supported by statistical tests to ensure they convey relevant phenotypic information and are clinically meaningful.

5. **Stability of Clusters**: Clusters must demonstrate stability through resampling techniques to confirm that their structure holds across different subsets of data.

6. **Clinical Utility**: Beyond statistical validation, clusters should prove clinically useful by providing interpretable outcomes and demonstrating unique treatment effects in clinical trials, validating their relevance and accuracy against standard diagnostic measures.

In summary, the article emphasizes rigorous statistical scrutiny and clinical relevance when using clustering techniques in medical data analysis.
## Links

- [Cluster Stability Assessment](https://darrendahly.github.io/post/cluster) : An overview of clustering methods and their stability in predicting outcomes.
- [Variable Clustering Techniques](https://hbiostat.org/rmsc/cony#fig-cony-redun) : A discussion on variable clustering versus patient clustering and their implications for statistical analysis.
- [Sparse Principal Components Analysis](https://hbiostat.org/rmsc/impred#sec-impred-sparsepc) : Explains the use of Sparse PCA for improving clustering results and handling multicollinearity.
- [Likelihood Ratio Tests for Clustering](https://hbiostat.org/rmsc/mle) : Details on using likelihood ratio tests to evaluate clustering effectiveness and cluster membership validity.
- [Validation of Cluster Analysis](https://fharrell.com/post/addvalue) : Discusses methods to validate clusters by ensuring they provide new prognostic information.

## Topics

![](topics/Concept/Patient%20Clustering)

![](topics/Concept/Variable%20Clustering)

![](topics/Concept/Sparse%20Principal%20Component%20Analysis%20PCA)

![](topics/Concept/Forced%20Choice%20Cluster%20Classification)

![](topics/Concept/Clinical%20Utility%20of%20Clustering)

![](topics/Concept/Bootstrapping%20for%20Stability%20Validation)