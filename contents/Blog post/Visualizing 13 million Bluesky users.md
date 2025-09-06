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

The author explores the visualization of 13 million Bluesky users, focusing on the follow graph. Bluesky, built on the AT protocol, allows real-time data streaming via a WebSocket firehose, which the author uses to collect follow and unfollow events, storing them in a SQLite database. The data is managed on a home server, with the follows table containing over half a billion rows, totaling around 30 GB.

The main challenge is rendering a graph with 13 million nodes and half a billion edges. The author uses a force-directed graph layout, inspired by physics simulations, where nodes repel each other and edges attract. The Barnes-Hut optimization is employed to reduce computational complexity. The author develops a multithreaded engine in Zig, named Andromeda, for this purpose, which is inspired by Gephi and the ForceAtlas2 paper.

However, force-directed layouts for large social networks result in "blobby" structures, showing major clusters but not local neighborhoods effectively. The author then explores dimensionality reduction techniques like UMAP, which provides better intermediate structure. UMAP's output is further refined using Andromeda to prevent overlapping points.

The visualization is enhanced with color, using k-means clustering and interpolation to highlight local structure. The final visualization includes 7.7 million nodes, with color representing follower count and cluster membership. The author notes the potential for new insights and features, such as a timeline of posts from accounts in view, and invites further ideas for improvement.
## Links

- [Barnes–Hut simulation](https://en.wikipedia.org/wiki/Barnes%E2%80%93Hut_simulation) : A Wikipedia page about the Barnes–Hut simulation, an algorithm used to optimize force calculations in n-body simulations, which is mentioned in the context of optimizing the force-directed graph layout for visualizing the Bluesky user graph.
- [N-body simulation](https://en.wikipedia.org/wiki/N-body_simulation) : A Wikipedia page about n-body simulations, which are used to simulate the dynamics of a system of particles interacting through forces like gravity or electromagnetism. This is relevant to the force-directed graph layout mentioned in the article.
- [nodevectors](https://github.com/VHRanger/nodevectors/) : A GitHub repository for nodevectors, an open-source toolkit for node embedding, which is used to generate embeddings for users in the Bluesky network before applying UMAP for visualization.

## Topics

![](topics/Tool/Andromeda)

![](topics/Concept/Force%20directed%20graph%20layout)

![](topics/Concept/Barnes%20Hut%20optimization)

![](topics/Concept/Node%20Embeddings)

![](topics/Concept/Natural%20Slider)

![](topics/Concept/UMAP)