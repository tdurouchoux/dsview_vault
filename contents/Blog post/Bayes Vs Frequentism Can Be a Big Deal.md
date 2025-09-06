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

The content discusses the debate between Bayesian and Frequentist statistical methods, particularly in the context of A/B testing. The author, Demetri Pananos, argues that the differences between these approaches are significant and that oversimplifying them can lead to poor decisions. Here are the key points:

1. **Common Misconceptions**: The author addresses four common arguments that minimize the differences between Bayesian and Frequentist methods:
   - "Flat" or "uninformative" priors often result in similar estimates as Frequentist analysis.
   - The likelihood dominates the prior in the limit of large samples.
   - Both methods will reach the same conclusion.
   - Informative priors are biased and/or subjective.

2. **Flat Priors and Hierarchical Models**: The author explains that using flat priors in hierarchical Bayesian models can lead to implausible estimates, contrary to the expectation that they would yield similar results to Frequentist analysis.

3. **Influence of Prior and Sample Size**: The author discusses how the influence of the prior on the posterior decreases as the sample size increases, but the rate of this decrease depends on the prior used. More informative priors require more data to overwhelm their influence.

4. **Decision Theory**: The author argues that treating Bayesian credible intervals as Frequentist confidence intervals ignores decades of decision theory. Bayesian methods make decision theory straightforward and can lead to different conclusions and decisions.

5. **Subjectivity and Transparency**: The author contends that informative priors are not inherently more subjective than other modeling choices in statistical analysis. Both Bayesian and Frequentist methods involve subjective decisions, and transparency and justification of assumptions are crucial.

The author concludes that Bayesian methods offer unique advantages, particularly in decision theory, and that oversimplifying the debate between Bayesian and Frequentist methods can lead to poor decisions.
## Links

- [Hidden Dangers of Non-Informative Priors](https://statmodeling.stat.columbia.edu/2013/11/21/hidden-dangers-noninformative-priors/) : A blog post discussing the potential pitfalls and hidden dangers of using non-informative priors in Bayesian analysis.
- [Chris Stucchio's Technical Whitepaper on SmartStats](https://www.chrisstucchio.com/pubs/VWO_SmartStats_technical_whitepaper.pdf) : A technical whitepaper by Chris Stucchio on SmartStats, which is likely related to statistical methods and experimentation.

## Topics

![](topics/Concept/Bayesian%20statistics)

![](topics/Concept/Frequentist%20statistics)