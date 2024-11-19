---
already_read: true
link: https://joelgustafson.com/posts/2024-11-12/vizualizing-13-million-bluesky-users?utm_campaign=Data_Elixir&utm_source=Data_Elixir_511
read_priority: 1
source: Data Elixir
tags:
- Data_Visualization
- Graph
type: Content
upload_date: '2024-11-19'
---

https://joelgustafson.com/posts/2024-11-12/vizualizing-13-million-bluesky-users?utm_campaign=Data_Elixir&utm_source=Data_Elixir_511
## Summary

The article discusses the visualization of 13 million BlueSky users, leveraging the platform's growth due to Twitter's issues. The author created an interactive map using the follow graph, treating follows as undirected edges. Data was collected via a WebSocket from BlueSky's relay service, filtering for follow events and storing them in a local SQLite database.

The visualization process involved rendering a graph with 13 million nodes and over half a billion edges. A force-directed layout was initially used, which simulates physical forces to position nodes. However, due to computational complexity, the Barnes-Hut optimization was applied to improve efficiency. The author developed a multithreaded engine named Andromeda for this purpose.

To enhance local neighborhood representation, the author explored dimensionality reduction techniques, specifically UMAP, which provided better intermediate structures than the force-directed approach. However, UMAP's clustering led to overlapping points, which were resolved by integrating Andromeda's force-directed layout.

Color coding was introduced to represent additional dimensions of information, using k-means clustering for hues and scaling lightness based on follower counts. The final visualization filtered out certain accounts, resulting in a clearer representation of the network's structure.

The author aims to add features for exploring the graph further, such as a sidebar for viewing posts from accounts in the current view, promoting a new way to explore social connections.
## Links

1. [Nonlinear dimensionality reduction](https://en.wikipedia.org/wiki/Nonlinear_dimensionality_reduction) - Overview of techniques for reducing the dimensionality of data, relevant for visualizing large graphs.
2. [N-body simulation](https://en.wikipedia.org/wiki/N-body_simulation) - Explanation of the computational problem related to simulating the forces in a system of particles, applicable to force-directed graph layouts.
3. [nodevectors](https://github.com/VHRanger/nodevectors/) - Open-source toolkit for generating node embeddings, useful for handling large graphs like the one discussed.
4. [Andromeda](https://github.com/nDimensional/andromeda) - The multithreaded engine developed for force-directed graph layout, relevant to the visualization techniques described.
5. [UMAP documentation](https://umap-learn.readthedocs.io/en/latest/plotting.html#diagnostic-plotting) - Documentation for UMAP, a dimensionality reduction technique used in the visualization process.
## Topics

![](topics/Concept/BlueSky)

![](topics/Tool/Andromeda)

![](topics/Concept/Graph%20Representation)