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

![](artefacts/rules_of_ml.pdf)
## Summary

This document outlines best practices for machine learning (ML) engineering based on insights from Google. It serves as a guide for practitioners with foundational knowledge to implement effective ML processes. The content is divided into four main phases, each containing specific rules.

**Before Machine Learning:**
1. Launch without ML if not necessary.
2. Prioritize metrics design and implementation.
3. Opt for ML over complex heuristics.

**Phase I: Your First Pipeline**
- Keep the initial model simple and focus on establishing robust infrastructure.
- Test infrastructure separately from ML components.
- Be cautious of dropped data when replicating pipelines.
- Transform heuristics into features or manage them externally.

**Monitoring:**
- Understand the freshness requirements for your system.
- Detect and address potential model issues pre-export.
- Document feature sets and assign ownership.

**Your First Objective:**
- Avoid overthinking when selecting an objective.
- Choose simple, observable metrics for initial optimization.
- Begin with interpretable models for easier debugging.

**Phase II: Feature Engineering**
- Plan to launch and iterate your models.
- Start with directly observed features that are easy to report.
- Explore features that generalize across contexts.
- Utilize specific features when appropriate and combine/modulate existing ones.

**Human Analysis:**
- Recognize that engineers are not typical end users; get diverse feedback.
- Measure differences between models to assess improvements.

**Training-Serving Skew:**
- Maintain consistency between training and serving environments to avoid performance drops.
- Avoid arbitrary data dropping during training.

**Phase III: Slowed Growth and Optimization:**
- Prioritize understanding misalignments in objectives.
- Simplicity in ensembles is essential for interpretability.
- When performance plateaus, seek qualitatively new sources of information.

Key takeaways include ensuring that metrics directly correlate with business goals, the importance of keeping models simple, and the necessity of rigorous monitoring and evaluation processes throughout the ML lifecycle. Employing established heuristics can facilitate smoother transitions as new features or models are integrated into the system. Lastly, understanding user behavior and continuously refining objectives are crucial for long-term success in ML applications.
## Topics

![](topics/Concept/Machine%20Learning%20Infrastructure)

![](topics/Concept/Feature%20Extraction%20and%20Creation)

![](topics/Concept/Monitoring%20and%20Metrics%20in%20ML%20Systems)

![](topics/Concept/Training%20Serving%20Skew)

![](topics/Concept/Model%20Evaluation%20and%20Decision%20Metrics)

![](topics/Concept/Heuristic%20Optimization%20in%20ML%20Systems)

![](topics/Concept/A%20B%20Testing%20for%20Model%20Performance)

![](topics/Concept/Model%20Maintenance%20and%20Iteration)