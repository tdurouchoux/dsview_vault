---
already_read: false
link: https://drbenvincent.github.io/posts/mcmc_grammar_of_graphics.html
read_priority: 5
relevance: 0
source: Data Elixir
tags:
- Statistics
type: Content
upload_date: '2025-05-07'
---

https://drbenvincent.github.io/posts/mcmc_grammar_of_graphics.html
## Summary

The post explores making Bayesian model plotting in Python more declarative by combining Bayesian models, grammar of graphics, and Python. The author highlights the pain points in current plotting methods, which often require manual data wrangling and a good understanding of the internal structure of the InferenceData object. The post presents a proof of concept for a more declarative approach using the plotnine package. The key steps include converting the arviz.InferenceData object to a tidy dataframe and then using plotnine to create plots declaratively. The author demonstrates this approach by plotting posterior predictive distributions and posterior distributions of slopes for each group. The summary emphasizes the advantages of the grammar of graphics approach, which allows for modular plot construction and focuses on what to plot rather than how to wrangle the data. The post concludes by noting that this approach has been available in R for some time and suggests that it could be appealing to Python users as well.
## Links

- [ArviZ Documentation](https://python.arviz.org/en/stable/api/generated/arviz.InferenceData.html#arviz.InferenceData) : Official documentation for the ArviZ library, specifically detailing the InferenceData object used for handling Bayesian model outputs in Python.
- [TidyBayes Documentation](https://mjskay.github.io/tidybayes/) : Documentation for the TidyBayes package, which provides tools for working with Bayesian models in a tidy and declarative manner, similar to the approach discussed in the blog post.

## Topics

![](topics/Library/PyMC)

![](topics/Library/ArviZ)

![](topics/Library/plotnine)

![](topics/Concept/Bayesian%20models)

![](topics/Concept/Grammar%20of%20graphics)

![](topics/Concept/Tidy%20Data)