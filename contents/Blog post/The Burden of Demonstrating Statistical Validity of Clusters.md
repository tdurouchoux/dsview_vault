---
already_read: true
link: https://www.fharrell.com/post/cluster/?utm_source=substack&utm_medium=email
read_priority: 3
source: Data science weekly
tags:
- Statistics
- Data_Visualization
- Data_Engineering
type: Content
upload_date: '2024-10-12'
---

https://www.fharrell.com/post/cluster/?utm_source=substack&utm_medium=email
## Summary

The article discusses the challenges and considerations in the statistical validation of patient clustering, often used to identify new phenotypes in medical research. Key points include:

- **Background**: Clustering is frequently misapplied in medicine, with many studies failing to align clustering results with clinical goals. The article critiques the validity of findings from studies like Ahlqvist et al., which claimed to identify diabetes subtypes without proper statistical validation.

- **Clustering Purpose**: Researchers must clarify the ultimate goal of clustering, questioning whether patient clustering or variable clustering better serves their objectives. Variable clustering retains more information and is less arbitrary.

- **Presentation of Results**: Forced-choice classifications (assigning patients to discrete clusters) can be misleading. A continuous approach, using distances from cluster centers or probabilities of cluster membership, is recommended.

- **Validation of Cluster Membership**: Adequacy of cluster membership must be verified, ensuring that clusters are compact and meaningful. Statistical tests should assess the prognostic information provided by cluster identifiers.

- **Stability of Clusters**: Clusters should be validated for stability through bootstrap methods, allowing the number of clusters to vary across resamples.

- **Clinical Validation**: Beyond statistical validation, clusters must demonstrate clinical usefulness, such as being interpretable and capturing differential treatment effects in clinical trials.

Overall, the article emphasizes the need for rigorous statistical and clinical validation of clustering methods in medical research to ensure meaningful and actionable results.
## Links

1. [Sparse Principal Components Analysis](https://hbiostat.org/rmsc/impred#sec-impred-sparsepc) - A useful tool that combines variable clustering with PCA to handle collinearities while providing a more sparse representation of patient baseline variables.
2. [Likelihood Ratio Tests](https://hbiostat.org/rmsc/mle) - Information on likelihood ratio tests which can be used to assess the prognostic information due to different sets of predictors in clustering.
3. [Ahlqvist et al. Diabetes Subtypes](https://www.thelancet.com/journals/landia/article/PIIS2213-8587(18)30124-4/fulltext) - A critical examination of the claims made by Ahlqvist et al. regarding the identification of new diabetes subtypes through clustering.
4. [Darren Dahly's Clustering Example](https://darrendahly.github.io/post/cluster) - A simple example illustrating the potential pitfalls of clustering algorithms in determining the correct number of clusters.
5. [Direct Modeling of Outcomes](https://fharrell.com/post/addvalue) - Discusses the advantages of direct modeling of outcomes over clustering for better prognostic stratification.
## Topics

![](topics/Concept/Patient%20Clustering)

![](topics/Concept/Variable%20Clustering)

![](topics/Library/Sparse%20Principal%20Components%20Analysis%20PCA)

![](topics/Concept/Forced%20Choice%20Cluster%20Classification)

![](topics/Concept/Cluster%20Stability%20Validation)