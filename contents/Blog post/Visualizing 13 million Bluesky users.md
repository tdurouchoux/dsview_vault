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

The author explores the visualization of Bluesky's social network, which has grown to 13 million users. The process involves collecting follow data via a WebSocket firehose, storing it in a SQLite database, and rendering a graph with 13 million nodes and half a billion edges. The author discusses the challenges and optimizations of force-directed graph layout, including the use of the Barnes-Hut optimization to reduce computational complexity. They developed a multithreaded engine called Andromeda for this purpose, inspired by Gephi and the ForceAtlas2 paper.

The author then experiments with UMAP, a dimensionality reduction technique, to improve the visualization. They use nodevectors for node embedding and UMAP for further reduction, but find that UMAP has limitations for their use case. They address these by using Andromeda to smooth out overlapping points.

The visualization is enhanced with color, using k-means clustering and interpolation for a visually appealing result. The author shares insights gained from exploring the graph, such as the visibility of bot rings and the potential for a new kind of social exploration tool. They plan to add a timeline feature to show posts from accounts in the current view. The author invites feedback and ideas for further development.
## Links

- [UMAP Plotting Guide](https://umap-learn.readthedocs.io/en/latest/plotting.html#diagnostic-plotting) : A guide on using UMAP for diagnostic plotting, which is relevant for understanding how to visualize high-dimensional data.
- [Graphviz Online](https://dreampuf.github.io/GraphvizOnline) : An online tool for creating and visualizing graphs using Graphviz, which can be useful for graph layout and visualization.
- [D3 Force-Directed Graph](https://observablehq.com/@d3/force-directed-graph/2) : An example of a force-directed graph using D3.js, which is relevant for understanding force-directed graph layouts.
- [Barnes-Hut Simulation](https://en.wikipedia.org/wiki/Barnes%E2%80%93Hut_simulation) : A Wikipedia article on the Barnes-Hut simulation, which is an optimization technique used in force-directed graph layouts.
- [NodeVectors GitHub](https://github.com/VHRanger/nodevectors/) : The GitHub repository for NodeVectors, a toolkit for node embedding, which is relevant for understanding how to derive embeddings for graph visualization.

## Topics

![[topics/Concept/UMAP)]]

![[topics/Model/GGVec)]]

![[topics/Tool/Andromeda)]]

![[topics/Concept/Natural Slider)]]

![[topics/Concept/Force directed graph layout)]]

![[topics/Concept/Barnes Hut optimization)]]

![[topics/Concept/Node Embeddings)]]