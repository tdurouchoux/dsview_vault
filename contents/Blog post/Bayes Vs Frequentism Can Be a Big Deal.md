---
already_read: false
link: https://www.geteppo.com/blog/bayes-vs-frequentism-can-be-a-big-deal
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Statistics
type: Content
upload_date: '2025-03-19'
---

https://www.geteppo.com/blog/bayes-vs-frequentism-can-be-a-big-deal
## Summary

The content discusses the debate between Bayesian and Frequentist statistical methods, particularly in the context of A/B testing. The author, Demetri Pananos, argues that the differences between these approaches are significant and that oversimplifying them can lead to poor decision-making. Here are the key points:

1. **Common Misconceptions**: The author addresses four common arguments that minimize the differences between Bayesian and Frequentist methods:
   - "Flat" or "uninformative" priors often result in similar estimates as Frequentist analysis.
   - The likelihood dominates the prior in the limit of large samples.
   - Both methods will reach the same conclusion.
   - Informative priors are biased and/or subjective.

2. **Bayesian Statistics**: The author explains how Bayesian statistics works, emphasizing the role of priors and posteriors. They note that while some models with flat priors may yield similar results to Frequentist analysis, Bayesian statistics is not limited to these models.

3. **Hierarchical Bayesian Models**: The author highlights the benefits of hierarchical Bayesian models, which can provide more accurate estimates and combat issues like the winner's curse. They argue that using a flat prior in such models can lead to implausible estimates.

4. **Influence of Priors**: The author discusses how the influence of the prior on the posterior depends on the prior used and the sample size. They note that more informative priors require more data to remove their influence.

5. **Decision Theory**: The author argues that treating Bayesian analysis as if it were Frequentist analysis ignores decades of decision theory. They provide an example where using decision theory led to a different conclusion than a null hypothesis significance test.

6. **Subjectivity of Priors**: The author argues that informative priors are not inherently more subjective than other modeling choices in statistical analysis. They emphasize the importance of transparency and justification of assumptions.

In summary, the author argues that the differences between Bayesian and Frequentist methods are significant and that oversimplifying them can lead to poor decision-making. They emphasize the benefits of Bayesian methods, particularly in the context of decision theory.
## Links

- [Eppo's Bayesian Aggregate Impact Estimator](https://docs.geteppo.com/experiment-analysis/reporting/scorecard/#bayesian-aggregate-impact-estimation) : Eppo's Bayesian Aggregate Impact Estimator documentation.
- [Hidden Dangers of Non-Informative Priors](https://statmodeling.stat.columbia.edu/2013/11/21/hidden-dangers-noninformative-priors/) : A blog post discussing the hidden dangers of using non-informative priors in Bayesian analysis.
- [Bayesian Statistics Documentation](https://docs.geteppo.com/experiment-analysis/#bayesian-statistics) : Eppo's documentation on Bayesian statistics, providing insights into Bayesian methods and their applications.

## Topics

![[topics/Concept/Winner s Curse]]

![[topics/Concept/Decision Theory]]

![[topics/Concept/Hierarchical Bayesian Modeling]]

![[topics/Concept/Frequentist Statistics]]

![[topics/Concept/Bayesian Statistics]]

![[topics/Concept/Posterior Distribution]]

![[topics/Concept/Prior Distribution]]

![[topics/Concept/Expected Value of Sample Information]]

![[topics/Concept/Expected Loss]]