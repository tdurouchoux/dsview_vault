---
type: Concept
---

Derived data in Scion refers to auxiliary data structures computed from changesets to enable efficient operations like blame, path history, and copy detection. These structures are defined recursively, allowing their values for a changeset to be computed from their values for its parents. Derived data can be computed eagerly or deferred, and its internal implementation can be optimized without changing the client. Scion uses derived data to support novel indices and operations that improve performance for large-scale repositories.