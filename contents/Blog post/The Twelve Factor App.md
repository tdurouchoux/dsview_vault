---
already_read: true
link: https://12factor.net/
read_priority: 0
relevance: 5
source: null
tags:
- Development_tool
type: Content
upload_date: '2026-03-28'
---

https://12factor.net/
## Summary

The Twelve-Factor App is a methodology for building software-as-a-service (SaaS) apps with 12 key principles:

1. **Codebase**: One codebase tracked in version control, with many deployments.
2. **Dependencies**: Explicitly declare and isolate dependencies.
3. **Config**: Store configuration in the environment.
4. **Backing services**: Treat them as attached resources.
5. **Build, release, run**: Separate build and run stages strictly.
6. **Processes**: Execute the app as stateless processes.
7. **Port binding**: Export services via port binding.
8. **Concurrency**: Scale out using the process model.
9. **Disposability**: Maximize robustness with fast startup and graceful shutdown.
10. **Dev/prod parity**: Keep development, staging, and production environments similar.
11. **Logs**: Treat logs as event streams.
12. **Admin processes**: Run admin tasks as one-off processes.

The methodology aims to improve portability, scalability, and maintainability of SaaS apps. It is language-agnostic and applies to apps using various backing services. The principles are based on extensive experience with Heroku platform and are designed to address common issues in modern app development.
## Links

- [The Twelve-Factor App on GitHub](https://github.com/twelve-factor/twelve-factor) : This link points to the official GitHub repository for the Twelve-Factor App methodology. It contains the source code, detailed documentation, and community contributions related to the twelve-factor principles.
- [Heroku's 12-Factor App Implementation](https://github.com/heroku/12factor) : This link leads to Heroku's implementation of the twelve-factor principles. It provides practical examples and tools for applying these methodologies in Heroku-based applications.
- [The New Heroku: Erosion Resistance and Explicit Contracts (Blog Post)](http://blog.heroku.com/archives/2011/6/28/the_new_heroku_4_erosion_resistance_explicit_contracts/) : This blog post by Heroku discusses the evolution of their platform, emphasizing erosion resistance and explicit contracts, which aligns with the twelve-factor app principles. It provides historical context and insights into modern app development practices.

## Topics

![[topics/Concept/Twelve Factor App]]

![[topics/Concept/Software as a Service SaaS]]

![[topics/Concept/Declarative Paradigm]]

![[topics/Concept/Portability Software]]

![[topics/Concept/Continuous Deployment]]

![[topics/Concept/Backing Services]]

![[topics/Concept/Stateless Processes]]

![[topics/Concept/Dev Prod Parity]]

![[topics/Concept/Concurrency Process Model]]

![[topics/Concept/Disposability Fast Startup and Graceful Shutdown]]