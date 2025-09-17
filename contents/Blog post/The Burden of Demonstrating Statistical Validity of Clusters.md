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

The article discusses the challenges and considerations in patient clustering for medical research, highlighting the lack of validation and alignment with clinical goals in many current applications. Key points include:

- **Background**: Patient clustering is often used to find new phenotypes, but many applications are not well thought out or validated. A study by Ahlqvist et al. is criticized for claiming to find new diabetes subtypes without proper clinical validation.

- **Purpose of Clustering**: Researchers should address basic questions such as the ultimate goal of clustering, whether the disease is all-or-nothing, and the best way to summarize results. Variable clustering is often more useful than patient clustering.

- **Presentation of Results**: Forced-choice classification is not always the best way to represent clusters. Continuous methods, such as using distances from cluster centers or probabilities of membership, are often more appropriate.

- **Validation of Clusters**: Clusters must be validated for adequacy of summarization and stability. This involves checking the compactness of clusters, comparing predictive information, and demonstrating new prognostic information.

- **Clinical Usefulness**: Ultimately, clusters need to be validated by demonstrating clinical usefulness, such as interpretability, homogeneity within clusters, and capturing differential treatment effects.

The article emphasizes the importance of careful validation and alignment with clinical goals in patient clustering.
## Links

- [Clustering Algorithms and Number of Clusters](https://x.com/MaartenvSmeden/status/970237614413570048) : Discussion on how clustering algorithms can easily get the wrong number of clusters when the true number is known.
- [Simple Example of Clustering](https://darrendahly.github.io/post/cluster) : A simple example showing that clustering can be trivial, such as distinguishing people older than 65 from those under 65.
- [Letter to the Editor on Diabetes Subtypes](https://www.thelancet.com/journals/landia/article/PIIS2213-8587(18)30124-4/fulltext) : A letter to the editor casting doubt on the assertion that new forms of diabetes have been identified through clustering.
- [Sparse Principal Components Analysis (PCA)](https://hbiostat.org/rmsc/impred#sec-impred-sparsepc) : Explanation of sparse PCA, which combines variable clustering with PCA to handle collinearities and provide a more sparse representation of patient baseline variables.
- [Assessing the Added Value of New Variables](https://fharrell.com/post/addvalue) : Guidance on how to assess the added value of new variables in predicting outcomes, including the use of likelihood ratio tests.

## Topics

![](topics/Concept/Patient%20Clustering)

![](topics/Concept/Variable%20Clustering)

![](topics/Concept/Sparse%20Principal%20Components%20Analysis%20PCA)

![](topics/Concept/Forced%20Choice%20Cluster%20Classification)

![](topics/Concept/Cluster%20Stability)