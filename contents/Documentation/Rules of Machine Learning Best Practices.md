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

This document outlines best practices for machine learning (ML) engineering, drawing from experiences at Google. It is structured into several phases, each with specific rules to guide practitioners.

**Terminology and Overview**: Key terms such as instance, label, feature, and model are defined. The document emphasizes that effective ML relies more on solid engineering and feature design than on complex algorithms.

**Before Machine Learning**: 
- Launch products without ML if unnecessary.
- Prioritize metrics design and implementation.
- Opt for ML over complex heuristics when data is available.

**ML Phase I: Your First Pipeline**:
- Keep the initial model simple and focus on infrastructure.
- Test infrastructure independently from ML components.
- Be cautious about data loss when copying pipelines.
- Convert heuristics into features or manage them externally.

**Monitoring**:
- Understand freshness requirements of your system.
- Detect issues before model export.
- Monitor for silent failures and ensure feature ownership and documentation.

**Your First Objective**:
- Choose a simple, observable metric for optimization.
- Start with interpretable models for easier debugging.
- Separate spam filtering from quality ranking.

**ML Phase II: Feature Engineering**:
- Plan for iterative launches and start with directly observed features.
- Explore generalizable features across contexts.
- Use specific features when applicable and combine existing features to create new ones.

**Human Analysis of the System**:
- Recognize that you are not a typical end user.
- Measure differences between models and prioritize utilitarian performance over predictive power.
- Identify patterns in errors to create new features.

**Training-Serving Skew**:
- Ensure training and serving processes are aligned to avoid discrepancies.
- Use importance weighting for sampled data instead of dropping it arbitrarily.
- Be cautious of data changes between training and serving.

**ML Phase III: Optimization and Complex Models**:
- Avoid wasting time on new features if misaligned objectives are the issue.
- Launch decisions should consider multiple metrics.
- Keep ensembles simple and focus on qualitative new sources of information when performance plateaus.

**Key Takeaways**:
- Prioritize solid infrastructure and feature design over complex algorithms.
- Monitor and document features and metrics rigorously.
- Understand the importance of aligning training and serving data to maintain model performance.
- Embrace simplicity in models and features to facilitate debugging and iteration.
## Topics

![](topics/Concept/Best%20Practices%20in%20Machine%20Learning)

![](topics/Concept/Machine%20Learning%20Pipeline)

![](topics/Concept/Feature%20Engineering)

![](topics/Concept/Monitoring%20and%20Maintenance)

![](topics/Product/TensorFlow)