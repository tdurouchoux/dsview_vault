---
already_read: false
link: https://drbenvincent.github.io/posts/mcmc_grammar_of_graphics.html
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Data_Visualization
- Python
- Statistics
type: Content
upload_date: '2025-05-07'
---

https://drbenvincent.github.io/posts/mcmc_grammar_of_graphics.html
## Summary

The post discusses the challenges of plotting Bayesian models in Python and explores a declarative approach using the grammar of graphics. The author highlights the pain points of using ArviZ for plotting, which often requires imperative coding and a deep understanding of the InferenceData object structure. The post then introduces a proof of concept for converting the InferenceData object into a tidy dataframe, enabling a more declarative plotting style with the plotnine library. The author demonstrates how to plot posterior predictive distributions and posterior distributions of model parameters using this approach. The key takeaway is that this method allows for more modular and intuitive plotting, aligning with the grammar of graphics philosophy. The post concludes by noting that while this approach may not result in one-line plots, it simplifies the plotting process by focusing on what to plot rather than how to manipulate the data.
## Links

- [ArviZ InferenceData Documentation](https://python.arviz.org/en/stable/api/generated/arviz.InferenceData.html#arviz.InferenceData) : Documentation for the ArviZ InferenceData object, which is used to store the results of Bayesian models and perform diagnostics and plotting.
- [TidyBayes Documentation](https://mjskay.github.io/tidybayes/) : Documentation for the TidyBayes package, which provides tools for working with Bayesian models in a tidy and declarative way.

## Topics

![](topics/Library/ArviZ)

![](topics/Library/PyMC)

![](topics/Library/Bambi)

![](topics/Library/plotnine)

![](topics/Concept/Bayesian%20statistics)

![](topics/Concept/MCMC)

![](topics/Concept/Posterior%20Predictive%20Distribution)

![](topics/Concept/Grammar%20of%20Graphics)