---
type: Concept
---

Dependency maps are data structures that represent the dependencies between modules in a software project. Typically implemented as a flat object, each key in the map is a file path mapped to the set of files that directly import from it (its dependents). This structure allows for precise identification of modules affected by changes, enabling efficient incremental updates and supporting features like Hot Module Replacement (HMR).