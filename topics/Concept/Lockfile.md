---
type: Concept
---

A lockfile is a file that records the exact versions of dependencies used in a project to ensure reproducibility. It locks the dependencies to specific versions, preventing inconsistencies that can arise from using different versions across environments. Pixi uses lockfiles to manage dependencies in a deterministic way, ensuring that the same environment can be recreated anywhere.