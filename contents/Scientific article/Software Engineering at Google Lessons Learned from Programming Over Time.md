---
already_read: false
link: https://jinwoongkim.net/images/software-engineering-at-google-lessons-learned-from-programming-over-time-1nbsped-1492082791-9781492082798_compress.pdf
read_priority: 5
relevance: 0
source: null
tags:
- DevOps
type: Content
upload_date: '2026-08-31'
---

https://jinwoongkim.net/images/software-engineering-at-google-lessons-learned-from-programming-over-time-1nbsped-1492082791-9781492082798_compress.pdf

## Summary

Software Engineering at Google by Titus Winters, Tom Manshreck, and Hyrum Wright explores the principles, culture, processes, and tools that enable Google to sustainably build and maintain software at scale.

- **Core Thesis** : Software engineering extends programming by integrating time, scale, and trade-offs into development, emphasizing sustainability and long-term maintainability over short-term functionality.
- **Time and Change** : Software must be designed to accommodate future changes, with policies and tools to manage upgrades, deprecations, and long-term maintenance.
- **Scale and Efficiency** : Systems and processes must scale linearly or better with growth in codebase size, team size, and computational resources.
- **Trade-offs and Costs** : Decisions must balance financial, resource, personnel, transaction, opportunity, and societal costs, with data-driven approaches and a willingness to revisit decisions as contexts change.
- **Hyrum’s Law** : With enough users, all observable behaviors of a system will be depended upon, making API stability and backward compatibility critical.

**Culture**
- **Teamwork** : Software development is a collective effort, with culture rooted in humility, respect, and trust to foster collaboration and psychological safety.
- **Knowledge Sharing** : Documentation, mentorship, and community engagement (e.g., office hours, mailing lists) are vital for scaling knowledge across teams.
- **Leadership** : Effective leaders focus on delegation, decision-making, and scaling teams, while avoiding micromanagement and fostering intrinsic motivation (autonomy, mastery, purpose).
- **Diversity and Inclusion** : Teams must account for bias, represent diverse user bases, and design inclusively to avoid marginalizing users or perpetuating inequities.

**Processes**
- **Code Review** : Mandatory for all changes, ensuring correctness, comprehension, consistency, and knowledge sharing, with tools like Critique integrating tightly with other systems (e.g., Code Search, Tricorder).
- **Testing** : Automated testing is central, with a focus on unit tests (80% of tests) for speed and maintainability, supplemented by larger tests for integration and end-to-end validation.
- **Test Doubles** : Fakes, stubs, and mocks are used judiciously to isolate components, with a preference for realism (fakes) over interaction testing to avoid brittleness.
- **Documentation** : Treated as code, with ownership, version control, and canonical sources to ensure clarity, consistency, and maintainability.
- **Deprecation** : Advisory or compulsory, with clear milestones, migration support, and enforcement mechanisms to remove obsolete systems and reduce technical debt.
- **Version Control** : A single monorepo (Piper) with a One-Version Rule simplifies dependency management, while trunk-based development and minimal branching improve collaboration.
- **Large-Scale Changes (LSCs)** : Tooling (e.g., Rosie) and processes enable sweeping updates across the codebase, with authorization, sharding, and review workflows to manage risk.

**Tools**
- **Build Systems** : Bazel (open-source counterpart: Blaze) enforces artifact-based builds, dependency management, and reproducibility, with distributed execution (Forge) and remote caching (ObjFS) for scalability.
- **Code Search** : A fast, global search tool with ranking, cross-references (Kythe), and integration with other systems (e.g., stack traces, documentation) to navigate and understand the codebase.
- **Static Analysis** : Tricorder and other tools integrate with workflows (e.g., code review, presubmits) to catch issues early, with a focus on developer happiness and low false-positive rates.
- **Continuous Integration/Delivery (CI/CD)** : TAP (continuous build) and other systems automate testing and deployment, with presubmit/postsubmit optimizations and hermetic testing to balance speed and reliability.
- **Compute as a Service (CaaS)** : Borg (precursor to Kubernetes) manages containerized workloads, with lessons on designing for failure, managing state, and choosing between batch/serving architectures.

**Key Takeaways**
- **Sustainability** : Prioritize long-term maintainability, with policies and tools to manage change, scale, and trade-offs.
- **Automation** : Invest in tooling to reduce toil, enable consistency, and scale processes (e.g., builds, tests, reviews).
- **Collaboration** : Foster a culture of knowledge sharing, inclusive design, and psychological safety to scale teams effectively.
- **Iteration** : Embrace incremental improvements, data-driven decisions, and the ability to revisit past choices as systems evolve.
- **Trade-offs** : Explicitly weigh costs (e.g., compute, human time) and benefits, avoiding one-size-fits-all solutions.

## Links



## Topics

![[topics/Platform/Google s Monorepo]]

![[topics/Tool/Piper]]

![[topics/Tool/Bazel]]

![[topics/Tool/Code Search]]

![[topics/Tool/Critique]]

![[topics/Tool/Tricorder]]

![[topics/Tool/Blaze]]

![[topics/Concept/Hyrum s Law]]

![[topics/Concept/Large Scale Changes LSCs]]

![[topics/Platform/Forge]]