---
already_read: false
link: https://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf
read_priority: 1
source: null
tags:
- MlOps
type: Content
upload_date: '2022-09-15'
---

![](artefacts/rules_of_ml.pdf)
## Summary

This document outlines best practices for machine learning (ML) engineering, drawing from experiences at Google. It is structured into several phases, each with specific rules aimed at improving the development and deployment of ML systems.

**Key Rules and Phases:**

1. **Before Machine Learning**: 
   - Launch products without ML if unnecessary.
   - Prioritize metrics design and implementation.
   - Prefer ML over complex heuristics.

2. **Your First Pipeline**:
   - Keep the initial model simple and ensure robust infrastructure.
   - Test infrastructure independently from ML components.
   - Be cautious of data loss when copying pipelines.
   - Transform heuristics into features or manage them externally.

3. **Monitoring**:
   - Understand freshness requirements of your system.
   - Detect issues before model export.
   - Monitor for silent failures and ensure feature ownership and documentation.

4. **Your First Objective**:
   - Don’t overthink the choice of objective; keep it simple and observable.
   - Start with interpretable models for easier debugging.
   - Separate spam filtering from quality ranking.

5. **Feature Engineering**:
   - Plan for iterative launches and start with directly observed features.
   - Use specific features and combine existing ones to create new, understandable features.
   - Clean up unused features to avoid technical debt.

6. **Human Analysis of the System**:
   - Recognize that you are not a typical end user; gather external feedback.
   - Measure differences between models to assess changes.
   - Prioritize utilitarian performance over predictive power.

7. **Training-Serving Skew**:
   - Ensure consistency between training and serving environments.
   - Monitor for discrepancies that may affect performance.

8. **Slowed Growth and Optimization**:
   - Avoid adding new features if misaligned objectives are the issue.
   - Launch decisions should reflect long-term product goals.
   - Keep ensembles simple and focus on qualitative new information when performance plateaus.

9. **Diversity and Personalization**:
   - Don’t assume diversity, personalization, or relevance correlate with popularity.
   - Understand that user interests may differ across products.

The document emphasizes the importance of a solid pipeline, clear objectives, and continuous monitoring and iteration to ensure successful ML implementations. It also highlights the need for simplicity in models and features, advocating for a focus on practical performance metrics over complex algorithms.
## Topics

- [[topics/Concept/Best Practices in Machine Learning]]
- [[topics/Concept/Metrics Design and Implementation]]
- [[topics/Concept/Feature Engineering]]
- [[topics/Concept/Monitoring and Maintenance]]
- [[topics/Concept/Training-Serving Skew]]