---
already_read: true
link: https://github.com/python-graphblas/python-graphblas
read_priority: 0
relevance: 4
source: null
tags:
- Graph
type: Content
upload_date: '2026-09-11'
---

https://github.com/python-graphblas/python-graphblas

## Summary

python-graphblas is a Python library that provides high-performance sparse linear algebra for scalable graph analytics by wrapping the GraphBLAS C API.

**Overview**
- High-performance sparse linear algebra library for graph analytics
- Python wrapper for the GraphBLAS C API 2.0 specification
- Currently works with SuiteSparse:GraphBLAS, aims to support all GraphBLAS implementations

**Installation**
- Available via conda (`conda install -c conda-forge python-graphblas`) and pip (`pip install 'python-graphblas[default]'`)
- Optional dependencies: `pandas`, `matplotlib`, `scipy`, `networkx`

**Key Features**
- Follows the C-API 2.0 specification closely with Python syntax improvements
- Uses `<<` operator for assignment to separate output, mask, and accumulator from computation
- Supports delayed objects for lazy evaluation and performance optimization
- Provides a wide range of operations: mxm, mxv, vxm, eWiseAdd, eWiseMult, kronecker, transpose, etc.
- Supports extraction, assignment, apply, and reduce operations
- Allows creation of new vectors/matrices and properties extraction
- Supports context initialization for setting backend and blocking mode
- Enables performant user-defined functions using `numba`

**Interoperability**
- Connectors for `scipy.sparse`, `networkx`, and `numpy` arrays
- Facilitates communication with other network analysis libraries

**Resources**
- Documentation: [python-graphblas.readthedocs.io](https://python-graphblas.readthedocs.io/)
- Source: [GitHub](https://github.com/python-graphblas/python-graphblas)
- Community: Discord, weekly calls, GitHub discussions

## Links

- [Python-graphblas Documentation](https://python-graphblas.readthedocs.io/) : Comprehensive documentation for the Python-graphblas library, including installation guides, API references, FAQs, and usage examples.
- [GraphBLAS C API Specification](https://graphblas.org/docs/GraphBLAS_API_C_v2.0.0.pdf) : Official specification for the GraphBLAS C API version 2.0, which the Python-graphblas library closely follows for high-performance sparse linear algebra operations.
- [SuiteSparse:GraphBLAS User Guide](https://github.com/DrTimothyAldenDavis/GraphBLAS/raw/stable/Doc/GraphBLAS_UserGuide.pdf) : User guide for SuiteSparse:GraphBLAS, the C library that powers the python-graphblas Python bindings, covering implementation details and best practices.
- [graphblas-algorithms Repository](https://github.com/python-graphblas/graphblas-algorithms) : Repository containing algorithms built on top of the python-graphblas library, demonstrating scalable graph analytics and linear algebra operations.
- [Python-graphblas GitHub Repository](https://github.com/python-graphblas/python-graphblas) : The official GitHub repository for the python-graphblas library, including source code, issue tracking, discussions, and community contributions.


## Topics

![[topics/Library/python graphblas]]

![[topics/Library/SuiteSparse GraphBLAS]]

![[topics/Library/graphblas algorithms]]

![[topics/Concept/GraphBLAS]]

![[topics/Library/NetworkX]]

![[topics/Library/SciPy]]

![[topics/Library/Pandas]]

![[topics/Library/Matplotlib]]