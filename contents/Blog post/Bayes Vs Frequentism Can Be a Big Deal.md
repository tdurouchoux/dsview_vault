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

The article discusses the distinctions and debates surrounding Bayesian versus Frequentist statistics, particularly in the context of A/B testing. Key points include:

- The common arguments against Bayesian methods often oversimplify the nuances of statistical models and their assumptions.
- Bayesian Analysis: Bayesian methods begin with a prior belief about parameters, which is updated with data to form a posterior distribution. The prior can be informative or uninformative, influencing estimates differently.
- Flat or uninformative priors can lead to similar estimates as frequentist analyses, but this similarity does not capture the broader applicability and flexibility of Bayesian methods in various models.
- The claim that likelihood will eventually dominate prior in large samples depends on the prior's nature; more informative priors require larger datasets to diminish their influence.
- Bayesian methods allow for more advanced decision-making and can lead to different conclusions beyond mere significance testing, incorporating concepts like expected loss.
- The assertion that informative priors are biased or subjective is countered by recognizing that all statistical methods involve subjective choices. Emphasizing transparency in assumptions is crucial.
- The article encourages a deeper understanding of Bayesian analysis, highlighting its advantages in experimentation frameworks and decision-making over the simplistic dichotomy with frequentist methods.
## Links

- [Bayesian Aggregate Impact Estimation Documentation](https://docs.geteppo.com/experiment-analysis/reporting/scorecard/#bayesian-aggregate-impact-estimation) : A detailed guide on how Eppo implements Bayesian aggregate impact estimation in experimental analysis.
- [Bayesian Statistics Documentation](https://docs.geteppo.com/experiment-analysis/#bayesian-statistics) : Comprehensive documentation on Bayesian statistics as used in Eppo's experimentation framework.
- [Understanding Brandolini's Law](https://en.wikipedia.org/wiki/Brandolini%27s_law) : An explanation of Brandolini's Law, which highlights the difficulty of countering misinformation.
- [Hidden Dangers of Non-Informative Priors](https://statmodeling.stat.columbia.edu/2013/11/21/hidden-dangers-noninformative-priors/) : A blog post discussing the pitfalls of using non-informative priors in Bayesian analysis.
- [Expected Loss in Decision Making](https://www.chrisstucchio.com/pubs/VWO_SmartStats_technical_whitepaper.pdf) : A technical white paper discussing the concept of expected loss in decision-making, particularly relevant for Bayesian analysis.

## Topics

![](topics/Concept/Bayesian%20Statistics)

![](topics/Concept/Frequentist%20Statistics)

![](topics/Concept/A%20B%20Testing)

![](topics/Concept/Hierarchical%20Bayesian%20Modeling)

![](topics/Concept/Decision%20Theory)

![](topics/Tool/Eppo)