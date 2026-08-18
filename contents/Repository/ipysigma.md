---
already_read: true
link: https://github.com/medialab/ipysigma
read_priority: 0
relevance: 3
source: null
tags:
- Data_Visualization
type: Content
upload_date: '2026-08-18'
---

https://github.com/medialab/ipysigma

## Summary

ipysigma is a Jupyter widget for rendering interactive networks using sigma.js and graphology, compatible with networkx and igraph.

**Core functionality**
- Renders interactive graphs directly in Jupyter notebook cells
- Works with `networkx` or `igraph` graph objects
- Supports synchronized "small multiples" via `SigmaGrid` for comparative analysis

**Visual customization**
- Extensive control over node/edge visual properties (color, size, labels, borders, halos, pictograms, shapes)
- Supports both categorical (palettes) and continuous (gradients/scales) data mapping
- Default color palettes auto-generated via `iwanthue` (max 10 colors by default)
- Predefined scales: `lin`, `log`, `log+1`, `pow`, `sqrt`
- Predefined color gradients from d3-scale-chromatic (e.g., `Viridis`, `Inferno`)

**Data input flexibility**
- Accepts node/edge attributes, mappings, iterables, partitions, or callables as visual variables
- Supports networkx/igraph metrics (e.g., `g.degree`, `g.betweenness()`)
- Widget-side metrics computation (e.g., Louvain community detection via `node_metrics=["louvain"]`)

**Key features**
- ForceAtlas2 layout with configurable settings
- Label rendering controls (`label_grid_cell_size`, `label_density`, `show_all_labels`)
- Edge types: `arrow`, `triangle`, `rectangle`, `line`, `curve`
- Export options: `.to_html()`, `.render_snapshot()`, `Sigma.write_html()`
- Synchronization of layout/camera/selection across multiple views

**Installation**
- `pip install ipysigma` (requires `networkx` or `igraph`)
- Additional setup for Jupyter Notebook/Lab extensions if not auto-installed
- Google Colab support via `output.enable_custom_widget_manager()`

**API highlights**
- `Sigma(graph, **kwargs)` for single graph visualization
- `SigmaGrid(graph, views=[...], columns=N)` for multi-view comparison
- Methods: `.get_layout()`, `.get_camera_state()`, `.get_selected_node/edge()`

## Links

- [Jupyter](https://jupyter.org/) : Official website for Jupyter, an open-source project that provides interactive computing environments, including Jupyter Notebook, which is used to create and share documents containing live code, equations, visualizations, and narrative text.
- [sigma.js](https://www.sigmajs.org/) : Official website for sigma.js, a JavaScript library dedicated to graph drawing, enabling the rendering of interactive networks in web browsers.
- [graphology](https://graphology.github.io/) : Official documentation for graphology, a robust and efficient graph theory library for JavaScript, used for handling graph data structures and algorithms.
- [networkx](https://networkx.org/) : Official website for NetworkX, a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
- [igraph](https://igraph.readthedocs.io) : Documentation for igraph, a collection of network analysis tools with the emphasis on efficiency, portability, and ease of use, available in multiple programming languages including Python.


## Topics

![[topics/Library/ipysigma]]

![[topics/Library/sigma js]]

![[topics/Library/graphology]]

![[topics/Library/NetworkX]]

![[topics/Library/igraph]]

![[topics/Library/pelote]]

![[topics/Model/Louvain algorithm]]

![[topics/Concept/Interactive Visualization]]

![[topics/Concept/Visual variables in graph rendering]]