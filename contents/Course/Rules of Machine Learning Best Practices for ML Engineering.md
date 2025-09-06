---
already_read: false
link: https://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf
read_priority: 1
relevance: 0
source: null
tags:
- MlOps
type: Content
upload_date: '2022-09-15'
---

https://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf
## Summary

The document provides a comprehensive guide to machine learning (ML) engineering, focusing on best practices and practical advice. It is structured into several phases, each addressing different aspects of ML system development and deployment.

### Key Points:

1. **Before Machine Learning**:
   - **Rule #1**: Don't be afraid to launch a product without ML if it's not absolutely required.
   - **Rule #2**: Prioritize metrics design and implementation.
   - **Rule #3**: Choose ML over complex heuristics once you have data.

2. **ML Phase I: Your First Pipeline**:
   - **Rule #4**: Keep the first model simple and focus on infrastructure.
   - **Rule #5**: Test the infrastructure independently from the ML.
   - **Rule #6**: Be careful about dropped data when copying pipelines.
   - **Rule #7**: Turn heuristics into features or handle them externally.

3. **Monitoring**:
   - **Rule #8**: Know the freshness requirements of your system.
   - **Rule #9**: Detect problems before exporting models.
   - **Rule #10**: Watch for silent failures.
   - **Rule #11**: Give feature sets owners and documentation.

4. **Your First Objective**:
   - **Rule #12**: Don't overthink which objective to optimize.
   - **Rule #13**: Choose a simple, observable, and attributable metric for your first objective.
   - **Rule #14**: Starting with an interpretable model makes debugging easier.
   - **Rule #15**: Separate Spam Filtering and Quality Ranking in a Policy Layer.

5. **ML Phase II: Feature Engineering**:
   - **Rule #16**: Plan to launch and iterate.
   - **Rule #17**: Start with directly observed and reported features.
   - **Rule #18**: Explore with features of content that generalize across contexts.
   - **Rule #19**: Use very specific features when you can.
   - **Rule #20**: Combine and modify existing features to create new features in human-understandable ways.
   - **Rule #21**: The number of feature weights you can learn in a linear model is roughly proportional to the amount of data you have.
   - **Rule #22**: Clean up features you are no longer using.

6. **Human Analysis of the System**:
   - **Rule #23**: You are not a typical end user.
   - **Rule #24**: Measure the delta between models.
   - **Rule #25**: When choosing models, utilitarian performance trumps predictive power.
   - **Rule #26**: Look for patterns in the measured errors, and create new features.
   - **Rule #27**: Try to quantify observed undesirable behavior.
   - **Rule #28**: Be aware that identical short-term behavior does not imply identical long-term behavior.

7. **Training-Serving Skew**:
   - **Rule #29**: The best way to make sure that you train like you serve is to save the set of features used at serving time, and then pipe those features to a log to use them at training time.
   - **Rule #30**: Importance weight sampled data, don’t arbitrarily drop it!
   - **Rule #31**: Beware that if you join data from a table at training and serving time, the data in the table may change.
   - **Rule #32**: Re-use code between your training pipeline and your serving pipeline whenever possible.
   - **Rule #33**: If you produce a model based on the data until January 5th, test the model on the data from January 6th and after.
   - **Rule #34**: In binary classification for filtering (such as spam detection or determining interesting e-mails), make small short-term sacrifices in performance for very clean data.
   - **Rule #35**: Beware of the inherent skew in ranking problems.
   - **Rule #36**: Avoid feedback loops with positional features.
   - **Rule #37**: Measure Training/Serving Skew.

8. **ML Phase III: Slowed Growth, Optimization Refinement, and Complex Models**:
   - **Rule #38**: Don’t waste time on new features if unaligned objectives have become the issue.
   - **Rule #39**: Launch decisions will depend upon more than one metric.
   - **Rule #40**: Keep ensembles simple.
   - **Rule #41**: When performance plateaus, look for qualitatively new sources of information to add rather than refining existing signals.
   - **Rule #42**: Don’t expect diversity, personalization, or relevance to be as correlated with popularity as you think they are.
   - **Rule #43**: Your friends tend to be the same across different products. Your interests tend not to be.

### Related Work and Acknowledgements:
- The document references various related works and acknowledges contributions from several individuals.

### Appendix:
- Provides overviews of YouTube, Google Play, and Google Plus, which are commonly used as examples in the document.

This summary captures the main technical points and key takeaways from the document, focusing on the structured approach to ML engineering and the practical rules provided for each phase of the ML lifecycle.
## Links


## Topics

![](topics/Concept/Machine%20Learning%20Engineering)

![](topics/Concept/Training%20Serving%20Skew)