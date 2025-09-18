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

The author shares their experience and process for building interactive embedding visualizations, which are tools for exploring and understanding entity relationships. Embeddings represent entities as points in N-dimensional space, with similar entities placed nearby. The author's projects include Spotify Music Galaxy, Anime Atlas, and osu! Beatmap Atlas, each built using a refined process.

Key steps in the process include:
1. **Data Collection and Preparation**: Gather data and pre-filter entities to manage size and relevance.
2. **Building the Co-Occurrence Matrix**: Create a matrix where each entity's relationships are recorded, considering memory and performance optimizations.
3. **Sparse Entity Relationship Graph**: Use PyMDE to pre-process the co-occurrence matrix into a sparser graph, addressing density and weight issues.
4. **Generating the Initial Embedding**: Use PyMDE to create an initial high-dimensional embedding, evaluating its quality for structure and accuracy.
5. **Projecting Down to 2D**: Use tools like Emblaze with algorithms such as UMAP or t-SNE to project the embedding into 2D for visualization.
6. **Building the Visualization UI**: Develop a web-based UI using WebGL or WebGPU for rendering, ensuring performance and interactivity.

The author emphasizes the importance of experimenting with parameters and algorithms to achieve the best results. They conclude by summarizing the process and encouraging others to try building their own embedding visualizations.
## Links

- [PyMDE](https://pymde.org/) : PyMDE is a Python library implementing an algorithm called Minimum Distortion Embedding. It's the main workhorse of the embedding-generation process and very powerful + versatile. It can embed high-dimensional vectors or graphs natively, the latter of which we'll be using.
- [Emblaze](https://dig.cmu.edu/emblaze/emblaze/) : Emblaze is a Jupyter Notebook widget that lets you easily create, visualize, and compare embeddings using a variety of different algorithms.
- [UMAP](https://umap-learn.readthedocs.io/en/latest/parameters.html#n-neighbors) : UMAP is probably the most well-known embedding algorithm and for good reason: UMAP does a very good job of generating accurate embeddings that preserve both local and global structure well.
- [Pixi.JS](https://pixijs.com/) : Pixi is a library that I've used on several projects in the past with great success every time. It exposes a nice high-level API for rendering 2D graphics and uses WebGL or WebGPU to do it. It takes care of all the hard parts like scene layering, hit testing, animation, zooming/panning, etc. and lets you focus on building your tool
- [regl](https://github.com/regl-project/regl) : regl is a lightweight WebGL wrapper library used to render the embedding as native gl.POINTS. It allows to write a vertex and fragment shader from scratch to style them.

## Topics

![[topics/Concept/Text Embeddings)]]

![[topics/Concept/Co Occurrence Matrix)]]

![[topics/Library/Emblaze)]]

![[topics/Concept/t SNE)]]

![[topics/Concept/UMAP)]]

![[topics/Library/PyMDE)]]

![[topics/Concept/Embedding Visualizations)]]