---
type: Concept
---

Dependency maps are data structures used to represent the relationships between different modules or files in a software project. Typically implemented as a flat object, each key in a dependency map is a file path mapped to the set of files that directly import from it (its dependents). This structure allows developers to perform lookups to identify the closure of all modules potentially affected by changes, enabling precise identification of what needs to be reloaded. Dependency maps are crucial for implementing techniques like Hot Module Replacement (HMR) and can significantly streamline incremental updates in large codebases.