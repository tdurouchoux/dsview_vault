---
already_read: false
link: https://pythonspeed.com/articles/numpy-2/
read_priority: 1
relevance: 0
source: null
tags:
- Python
type: Content
upload_date: '2024-01-18'
---

https://pythonspeed.com/articles/numpy-2/
## Summary

NumPy 2 is an upcoming major release with backward-incompatible changes, which may impact scientific and data science Python code. Key points include:

1. **Potential Breakages**: NumPy 2 could break your code, direct dependencies, or indirect dependencies.
2. **Dependency Pinning**: Pinning dependencies is crucial to prevent automatic installation of NumPy 2 until you're ready.
3. **Preventing NumPy 2 Installation**: Add `numpy<2` to your dependency list to avoid installing NumPy 2 prematurely.
4. **Upgrading to NumPy 2**: Once dependencies support NumPy 2, remove the version restriction and update your code using the NumPy 2 migration guide.
5. **Automated Code Upgrades**: Use Ruff linter to automate code upgrades for NumPy 2 compatibility.
6. **Best Practices**: Regularly update dependencies and use lockfiles to pin all dependencies.

The article also offers consulting services and a newsletter for further learning.
## Links

- [NumPy 2.0 Migration Guide](https://numpy.org/devdocs/numpy_2_0_migration_guide.html) : This link points to the official NumPy 2.0 migration guide, which provides detailed instructions on how to upgrade your code to be compatible with NumPy 2.0. It includes information on deprecated APIs and how to replace them with new ones.

## Topics

![](topics/Library/NumPy)

![](topics/Library/Scikit%20learn)

![](topics/Library/SciPy)

![](topics/Library/Scikit%20Image)

![](topics/Library/Astropy)

![](topics/Library/Pandas)

![](topics/Tool/Ruff)