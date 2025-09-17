---
type: Library
---

A Python tool written in Rust designed to manage module dependencies in large Python projects. It enforces clear dependencies between modules, helps sync, validate, and visualize these dependencies, and generates dependency graphs. Tach allows defining public interfaces for modules, limiting imports to explicitly defined members, and deprecating dependencies over time. It integrates seamlessly into workflows like CI pipelines and pre-commit hooks.