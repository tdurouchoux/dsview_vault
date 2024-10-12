---
already_read: true
link: https://www.fharrell.com/post/cluster/?utm_source=substack&utm_medium=email
read_priority: 3
source: Data science weekly
tags:
- Statistics
- Data_Visualization
type: Content
upload_date: '2024-10-12'
---

https://www.fharrell.com/post/cluster/?utm_source=substack&utm_medium=email
## Summary

The article discusses the challenges and considerations in the statistical validation of patient clustering, often used to identify new phenotypes in medical research. Key points include:

- **Background**: Clustering is frequently misapplied in medicine, with many studies failing to align clustering results with clinical goals. The validity of clusters is often unverified, leading to potentially misleading conclusions.

- **Clustering Purpose**: Researchers must clarify the ultimate goal of clustering, whether it is to identify patient subgroups or to enhance clinical prediction models. Variable clustering may be more effective than patient clustering, as it retains more information and better handles redundancies.

- **Presentation of Results**: Forced-choice classifications (assigning patients to discrete clusters) can be misleading. A continuous approach, using distances from cluster centers or probabilities of cluster membership, is recommended for better representation.

- **Validation of Cluster Membership**: Adequate validation of cluster membership is crucial. This includes assessing the compactness of clusters and ensuring that cluster identifiers convey meaningful prognostic information.

- **Stability of Clusters**: Clusters should be validated for stability through methods like bootstrapping, allowing the number of clusters to vary across resamples.

- **Clinical Validation**: Beyond statistical validation, clusters must demonstrate clinical usefulness, such as being interpretable and capturing differential treatment effects in clinical trials. 

Overall, the article emphasizes the need for rigorous statistical and clinical validation of clustering methods in medical research to ensure their reliability and applicability.
## Links

1. [diabetes was ever a binary diagnosis](https://www.acpjournals.org/doi/10.7326/0003-4819-149-3-200808050-00010) - Discusses the misconception of diabetes as a binary diagnosis and its implications in clustering.
2. [to have found 5 diabetes subtypes](https://www.thelancet.com/journals/landia/article/PIIS2213-8587(18)30051-2) - Examines the claims of identifying diabetes subtypes through statistical analysis.
3. [clustering algorithms easily get the wrong number of clusters](https://x.com/MaartenvSmeden/status/970237614413570048) - Highlights issues with clustering algorithms in determining the correct number of clusters.
4. [a simple example](https://darrendahly.github.io/post/cluster) - Provides a straightforward illustration of clustering challenges.
5. [Sparse principal components analysis](https://hbiostat.org/rmsc/impred#sec-impred-sparsepc) - Discusses a method that combines variable clustering with PCA to handle collinearities.
## Topics

- [[topics/Concept/Patient Clustering]]
- [[topics/Concept/Variable Clustering]]
- [[topics/Concept/Principal Components Analysis (PCA)]]
- [[topics/Concept/Forced-Choice Cluster Classification]]
- [[topics/Concept/Cluster Stability Validation]]