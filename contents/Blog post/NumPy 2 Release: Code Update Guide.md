---
already_read: false
link: https://pythonspeed.com/articles/numpy-2/
read_priority: 1
source: null
tags:
- Python
- Data_Engineering
type: Content
upload_date: '2024-01-18'
---

https://pythonspeed.com/articles/numpy-2/
## Summary

NumPy 2 is set to release a candidate on February 1, 2024, with a final version following shortly after. This major update is backwards incompatible, which may require code adjustments for applications relying on NumPy, as well as for libraries that depend on it, such as Pandas and Scikit-Learn.

Key points include:

1. **Potential Breakage**: Applications may break due to direct use of NumPy APIs, or through dependencies that are not yet compatible with NumPy 2.
2. **Dependency Management**: It's crucial to pin dependencies to specific versions to avoid automatic upgrades that could lead to breakage. This involves maintaining a direct dependency list and a lock file.
3. **Installation Restrictions**: Initially, users should restrict installations to NumPy 1.x by specifying `numpy<2` in their dependency configurations.
4. **Upgrade Process**: Once dependencies are confirmed compatible, users should remove the restriction and update their code according to the NumPy 2 migration guide. The Ruff linter can automate some of this code updating.
5. **Best Practices**: Regularly update dependencies and use lockfiles to manage both direct and transitive dependencies effectively.

Overall, preparation for NumPy 2 involves careful dependency management and proactive code updates to ensure compatibility.
## Links

1. [Is incompatible with NumPy 2](https://github.com/scikit-image/scikit-image/issues/7282) - Discussion on the compatibility issues of the scikit-image library with NumPy 2.
2. [NumPy 2 migration guide](https://numpy.org/devdocs/numpy_2_0_migration_guide.html) - Official guide for migrating code to be compatible with NumPy 2.
## Topics

- [[topics/Library/NumPy]]
- [[topics/Library/Ruff]]
- [[topics/Concept/Dependency Management]]
- [[topics/Concept/Lockfile]]
- [[topics/Concept/Versioning]]