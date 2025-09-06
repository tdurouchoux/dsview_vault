---
already_read: false
link: https://cprimozic.net/blog/building-embedding-visualizations-from-user-profiles/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Visualization
- Data_Analysis
type: Content
upload_date: '2024-05-29'
---

https://cprimozic.net/blog/building-embedding-visualizations-from-user-profiles/
## Summary

The author shares their experience and process for building interactive embedding visualizations, which are tools for exploring and understanding entity relationships in a free-form manner. Embeddings represent entities as points in N-dimensional space, with similar entities placed nearby. The author has created several projects, including Spotify Music Galaxy, Anime Atlas, and osu! Beatmap Atlas, to demonstrate the potential of these visualizations.

The process involves several steps:

1. **Data Collection and Preparation**: Gather data and pre-filter it to reduce cardinality. Create an ID to index mapping for easier reference.

2. **Building the Co-Occurrence Matrix**: Create a square matrix where each cell represents the co-occurrence of two entities. Consider memory and performance optimizations, such as using sparse matrices and numba for faster computation.

3. **Building a Sparse Entity Relationship Graph**: Use PyMDE's preserve_neighbors function to sparsify the co-occurrence matrix and address issues with dense graphs. Key parameters include n_neighbors and embedding_dim.

4. **Generating the Initial Embedding**: Use PyMDE to generate an initial embedding. Evaluate the quality of the embedding by looking for structure and visual appeal.

5. **Projecting Down to 2D**: Use algorithms like UMAP or t-SNE to project the high-dimensional embedding down to 2D. Emblaze is a useful tool for comparing different algorithms and parameters.

6. **Building the Visualization UI**: Create a web application to render the 2D embedding. Use WebGL or WebGPU-powered libraries like Pixi.JS for better performance with large datasets.

The author concludes by summarizing the entire process and encouraging others to try building their own embedding visualizations. They also express interest in hearing about others' experiences using their process.
## Links

- [osu! Beatmap Atlas](https://osu-atlas.ameo.dev/) : Interactive visualization of osu! beatmaps using embedding techniques.
- [Spotify Music Galaxy](https://galaxy.spotifytrack.net/) : Interactive 3D visualization of Spotify artists based on user listening data.
- [PyMDE Documentation](https://pymde.org/) : Documentation for PyMDE, a Python library for Minimum Distortion Embedding.

## Topics

![](topics/Concept/Text%20Embeddings)

![](topics/Concept/Embedding%20Visualizations)

![](topics/Library/PyMDE)

![](topics/Concept/Co%20Occurrence%20Matrix)

![](topics/Concept/Sparse%20Entity%20Relationship%20Graph)

![](topics/Concept/t%20SNE)

![](topics/Library/Emblaze)

![](topics/Concept/UMAP)