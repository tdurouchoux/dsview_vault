---
already_read: false
link: https://cprimozic.net/blog/building-embedding-visualizations-from-user-profiles/
read_priority: 1
relevance: 0
source: null
tags:
- Data_Visualization
type: Content
upload_date: '2024-05-29'
---

https://cprimozic.net/blog/building-embedding-visualizations-from-user-profiles/
## Summary

The article discusses the process and insights gained from building interactive embedding visualizations across various projects, focusing on the significance of embeddings and their visual representations.

**Background on Embeddings**: Embeddings represent entities as points in N-dimensional space, capturing complex relationships. Projection to 2D or 3D is necessary for human comprehension.

**Purpose of Embedding Visualizations**: They provide an exploratory method for understanding relationships, overcoming the limitations of traditional recommendation systems.

**Projects**: Notable creations include:
- **Spotify Music Galaxy**: A 3D visualization based on Spotify data.
- **Anime Atlas**: A 2D visualization using MyAnimeList data.
- **osu! Beatmap Atlas**: A dynamic visualization using gameplay data from the rhythm game osu!.

**Data Collection and Preparation**: Key steps include establishing similarity metrics and pre-filtering data to manageable sizes (10k-50k entities). Essential components are co-occurrence matrices and entity indexing.

**Building Co-Occurrence Matrix**: The article emphasizes performance and memory considerations since creating dense matrices can be resource-intensive. Efficient coding practices and libraries like Numba can improve performance.

**Building Sparse Entity Relationship Graph**: Pre-processing with PyMDE helps manage the density of co-occurrence graphs. Adjusting parameters like `n_neighbors` and `embedding_dim` significantly influences the embedding quality.

**Generating the Initial Embedding**: Embeddings can be generated simply using libraries like PyMDE, with early evaluations indicating quality based on density and structure.

**Projecting Down to 2D**: t-SNE and UMAP are highlighted as effective 2D projection methods. UMAP preserves both local and global structure, while t-SNE emphasizes local structure, each suited for different visualization needs.

**Visualization UI**: Web-based visualizations using libraries such as Pixi.JS facilitate the interaction and rendering of large datasets. Performance issues encountered with SVG led to the decision to use GPU-accelerated libraries.

**Conclusion**: The outlined process includes data collection, matrix construction, graph sparsification, high-dimensional embedding, and 2D projection, resulting in effective visual tools that reveal relationships in complex datasets. The author encourages exploring embedding visualizations and shares openness to feedback on implemented processes.
## Links

- [PixiJS - 2D WebGL Renderer](https://pixijs.com/) : A 2D WebGL renderer that allows developers to create visually appealing graphics and animations with ease.
- [PyMDE - Minimum Distortion Embedding](https://pymde.org/) : A powerful Python library for creating dimensionality-reduced embeddings from high-dimensional spaces.
- [UMAP Documentation](https://umap-learn.readthedocs.io/en/latest/parameters.html#n-neighbors) : Official documentation for UMAP, a widely-used algorithm for dimension reduction that is particularly effective for visualizing high-dimensional data.
- [Emblaze - Interactive Embedding Visualization](https://dig.cmu.edu/emblaze/emblaze/) : A tool that allows users to create, visualize, and compare embeddings interactively using various algorithms.
- [REGL - Functional WebGL for JavaScript](https://github.com/regl-project/regl) : A lightweight wrapper around WebGL that simplifies the rendering process and enhances performance for graphics applications.

## Topics

![](topics/Concept/Embeddings)

![](topics/Library/PyMDE)

![](topics/Library/UMAP)

![](topics/Library/t%20SNE)

![](topics/Tool/Emblaze)

![](topics/Concept/Co%20Occurrence%20Matrix)

![](topics/Concept/Sparsity%20in%20Embeddings)

![](topics/Concept/K%20Nearest%20Neighbors%20KNN)