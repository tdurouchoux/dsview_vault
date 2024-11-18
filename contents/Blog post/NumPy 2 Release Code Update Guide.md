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

NumPy 2 is set to release a candidate on February 1, 2024, with a final version following shortly after. This major release will be backwards incompatible, potentially affecting applications that rely on NumPy, including popular libraries like Pandas and Scikit-Learn. Key points include:

1. **Potential Breakage**: Applications may break due to:
   - Direct use of NumPy APIs.
   - Incompatibility of directly used libraries.
   - Incompatibility of transitive dependencies.

2. **Dependency Management**: It's crucial to pin dependencies to avoid automatic upgrades to NumPy 2. This involves maintaining a direct dependency list and a lock file to ensure reproducibility.

3. **Steps to Prepare**:
   - **Step 1**: Restrict NumPy version in your dependencies (e.g., `numpy<2`).
   - **Step 2**: Wait for your dependencies to become compatible with NumPy 2.
   - **Step 3**: Remove the version restriction and update your code as per the migration guide.

4. **Code Upgrade**: Use the Ruff linter to automate code updates for compatibility with NumPy 2. It can identify and fix deprecated usages.

5. **Best Practices**: Regularly update dependencies, use lockfiles, and consider preemptive version limitations to mitigate future breakages.

Overall, proactive management of dependencies and code updates is essential to ensure a smooth transition to NumPy 2.
## Links

1. [NumPy 2.0 Migration Guide](https://numpy.org/devdocs/numpy_2_0_migration_guide.html) - Official guide for migrating to NumPy 2.0, detailing changes and how to update your code.
2. [scikit-image GitHub Issue](https://github.com/scikit-image/scikit-image/issues/7282) - Discussion on the compatibility of scikit-image with NumPy 2, relevant for users of this library.
3. [Sciagraph Profiler](https://sciagraph.com/?mtm_campaign=end_of_article) - Tool for profiling Python code to identify performance and memory bottlenecks, useful for optimizing data science applications.
## Topics

![](topics/Library/NumPy)

![](topics/Library/Ruff)

![](topics/Concept/Dependency%20Management)

![](topics/Product/Sciagraph%20Profiler)

![](topics/Concept/Lockfile)