---
already_read: false
link: https://cprimozic.net/blog/building-embedding-visualizations-from-user-profiles/#building-a-sparse-entity-relationship-graph
read_priority: 1
source: null
tags:
- Data_Visualization
- Dimensionality_reduction
- Deep_Learning
type: Content
upload_date: '2024-05-29'
---

https://cprimozic.net/blog/building-embedding-visualizations-from-user-profiles/#building-a-sparse-entity-relationship-graph
## Summary

The content discusses the author's experiences and insights gained from building interactive embedding visualizations, focusing on the process and techniques used. 

Key points include:

- **Background on Embeddings**: Embeddings represent entities as points in N-dimensional space, capturing complex relationships. High-dimensional embeddings are often projected to 2D or 3D for visualization.

- **Purpose of Embedding Visualizations**: They facilitate exploratory data analysis, allowing users to uncover hidden relationships in data, contrasting with traditional recommendation systems.

- **Projects**: The author has created several projects, including the Spotify Music Galaxy, Anime Atlas, and osu! Beatmap Atlas, each utilizing different data sources and visualization techniques.

- **Data Collection and Preparation**: Emphasizes the importance of defining similarity metrics, pre-filtering data to manage cardinality, and creating a co-occurrence matrix to represent relationships.

- **Building the Co-Occurrence Matrix**: Discusses memory and performance considerations, recommending sparse matrix representations for large datasets and using libraries like numba for performance optimization.

- **Sparse Entity Relationship Graph**: Introduces PyMDE for preprocessing and embedding generation, highlighting the importance of parameters like n_neighbors and embedding_dim.

- **Generating Initial Embedding**: After preprocessing, the embedding is generated, and its quality is evaluated based on structure and visual appeal.

- **Projecting Down to 2D**: UMAP and t-SNE are recommended for projecting high-dimensional embeddings to 2D, each with distinct characteristics and parameters to tune.

- **Building the Visualization UI**: The author advocates for web applications using WebGL or WebGPU for rendering, emphasizing performance and user experience.

- **Conclusion**: Summarizes the process of creating embedding visualizations, encouraging others to explore this approach for data analysis.

Overall, the content provides a comprehensive overview of the techniques and considerations involved in creating effective interactive embedding visualizations.
## Links

1. [PyMDE Documentation](https://pymde.org/api/index.html#pymde.preserve_neighbors) - Official documentation for the PyMDE library, which implements Minimum Distortion Embedding and includes preprocessing routines for embedding generation.
2. [UMAP Documentation](https://umap-learn.readthedocs.io/en/latest/parameters.html#n-neighbors) - Comprehensive guide on UMAP, an algorithm for dimensionality reduction and visualization, including key parameters like n_neighbors.
3. [PixiJS](https://pixijs.com/) - A popular 2D rendering library that uses WebGL for high-performance graphics, suitable for building interactive visualizations.
4. [Emblaze](https://dig.cmu.edu/emblaze/emblaze/) - A Jupyter Notebook widget for creating, visualizing, and comparing embeddings using various algorithms, ideal for embedding visualization projects.
5. [REGL](https://github.com/regl-project/regl) - A functional WebGL library that simplifies the process of rendering graphics, useful for custom visualizations in embedding projects.
## Topics

![](topics/Library/PyMDE)

![](topics/Library/Emblaze)

![](topics/Concept/Co%20Occurrence%20Matrix)