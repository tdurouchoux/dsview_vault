---
already_read: false
link: https://pythonspeed.com/articles/numpy-2/
read_priority: 1
relevance: 0
source: null
tags:
- Python
- Development_tool
type: Content
upload_date: '2024-01-18'
---

https://pythonspeed.com/articles/numpy-2/
## Summary

NumPy 2 is an upcoming major release with backward-incompatible changes, which may impact scientific and data science Python code. The article outlines steps to prevent breakage and update code:

1. **Potential Breakage**: NumPy 2 could break your code, direct dependencies, or indirect/transitive dependencies.
2. **Pin Dependencies**: Use lock files to pin dependencies to specific versions, ensuring reproducibility.
3. **Prevent NumPy 2 Installation**: Initially, restrict NumPy to version 1.x by adding `numpy<2` to your dependency list.
4. **Wait for Dependency Updates**: Ensure all direct and indirect dependencies support NumPy 2 before upgrading.
5. **Upgrade Code and Dependencies**: Remove the NumPy version restriction, update code using the NumPy 2 migration guide, and use Ruff linter to automate code upgrades.
6. **Be Prepared**: Regularly update dependencies and consider pre-emptive version limitations for libraries using semantic versioning.

The article also briefly mentions the Sciagraph profiler for identifying performance and memory bottlenecks in data processing code, and a newsletter for learning practical tools and techniques in Python performance and Docker packaging.
## Links

- [NumPy 2.0 Migration Guide](https://numpy.org/devdocs/numpy_2_0_migration_guide.html) : This link points to the official NumPy 2.0 migration guide, which provides detailed instructions on how to update your code to be compatible with NumPy 2.0. It includes information on deprecated APIs and how to replace them.

## Topics

![[topics/Library/Ruff)]]

![[topics/Library/Scikit Learn)]]

![[topics/Library/Pandas)]]

![[topics/Library/SciPy)]]

![[topics/Library/Astropy)]]

![[topics/Library/NumPy)]]

![[topics/Library/Sciagraph)]]

![[topics/Library/Scikit Image)]]