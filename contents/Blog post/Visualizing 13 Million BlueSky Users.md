---
already_read: true
link: https://joelgustafson.com/posts/2024-11-12/vizualizing-13-million-bluesky-users
read_priority: 1
relevance: 0
source: Data Elixir
tags:
- Data_Visualization
- Graph
type: Content
upload_date: '2024-11-19'
---

https://joelgustafson.com/posts/2024-11-12/vizualizing-13-million-bluesky-users
## Summary

The article discusses the visualization of user interactions on Bluesky, a growing social network with over 13 million users, utilizing its follow graph. The author, Joel Gustafson, details the process of capturing and processing data through a WebSocket service, which aggregates follow events in real time. The follow graph is simplified to treat each follow as a single edge.

For rendering the graph of 13 million nodes and half a billion edges, a force-directed layout algorithm is employed, but is optimized using Barnes-Hut to reduce computational complexity from O(n^2) to O(n log(n)). A custom multithreaded engine called Andromeda, developed in Zig, facilitates this visualization. 

However, traditional force-directed layouts result in bland “blobby” structures, leading the author to explore dimensionality reduction techniques like UMAP. Although UMAP efficiently generates embeddings for visualization, it tends to create overlapping clusters, prompting the need for custom adjustments to smooth the layout.

To enhance the visualization, color-coding based on k-means clustering in the embedding space is used, with hues derived to visually differentiate clusters. Additional features for interaction, such as a sidebar for post timelines, are envisioned to further enhance user engagement with the visualization.

Key Takeaways:
- Data is gathered via real-time WebSocket from the Bluesky relay service.
- Force-directed layout with Barnes-Hut optimization is applied for graph rendering.
- UMAP is used for dimensionality reduction, though it requires additional smoothing.
- Color-coded clusters enhance visual differentiation.
- Future enhancements may include interactive timelines for contextual engagement.
## Links

- [Interactive BlueSky User Map](https://aurora.ndimensional.xyz/) : An interactive visualization tool for exploring users on the BlueSky platform.
- [Dagre - Graph Layout engine](https://github.com/dagrejs/dagre/wiki) : A library used for creating directed graphs, including algorithms for rendering layouts.
- [Force-Directed Graph Tutorial by D3.js](https://observablehq.com/@d3/force-directed-graph/2) : A tutorial on creating force-directed graphs using D3.js, which can be helpful for understanding graph visualizations.
- [Node Embedding Toolkit - Nodevectors](https://github.com/VHRanger/nodevectors/) : A repository containing an open-source toolkit for generating node embeddings, useful for large scale graph analysis.
- [UMAP Documentation](https://umap-learn.readthedocs.io/en/latest/plotting.html#diagnostic-plotting) : The official documentation for UMAP, providing insights into its functionality and examples for dimensionality reduction.

## Topics

![](topics/Concept/Graph%20Layout%20Algorithms)

![](topics/Tool/Andromeda)

![](topics/Library/UMAP)

![](topics/Library/nodevectors)

![](topics/Dataset/BlueSky%20Network%20Data)

![](topics/Concept/Dimensionality%20Reduction)