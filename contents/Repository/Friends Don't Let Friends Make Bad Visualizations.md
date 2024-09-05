---
already_read: false
link: https://github.com/cxli233/FriendsDontLetFriends?utm_source=substack&utm_medium=email
read_priority: 1
source: null
tags:
- Data_Visualization
type: Content
upload_date: '2024-01-25'
---

https://github.com/cxli233/FriendsDontLetFriends?utm_source=substack&utm_medium=email
## Summary

The repository "FriendsDon'tLetFriends" by Chenxin Li critiques common data visualization practices that can lead to misleading interpretations. Key points include:

1. **Bar Plots for Mean Separation**: Avoid using bar plots for comparing means across groups without checking distributions.
2. **Violin Plots for Small Samples**: Violin plots are ineffective with small sample sizes as they can misrepresent distributions.
3. **Bidirectional Color Scales**: Use unidirectional color scales for unidirectional data to avoid confusion.
4. **Bar Plot Meadows**: Multi-factorial data should be presented thoughtfully rather than in cluttered bar plots.
5. **Heatmaps**: Always reorder rows and columns for clarity and check for outliers that can skew interpretations.
6. **Data Range Checks**: Ensure to check the range of data at each factor level to avoid misleading conclusions.
7. **Network Graph Layouts**: Experiment with different layouts for network graphs to enhance interpretability.
8. **Position vs. Length**: Distinguish between position-based and length-based visualizations to prevent misinterpretation.
9. **Pie Charts**: Avoid pie charts due to difficulties in comparing angles; prefer stacked bar charts.
10. **Concentric Donuts**: These can mislead due to varying arc lengths; use stacked bars instead.
11. **Color Scales**: Avoid red/green and rainbow color scales; opt for colorblind-friendly alternatives like viridis.
12. **Reordering Stacked Bar Plots**: Optimize the order of bars in stacked plots for better clarity.
13. **Mixing Visualization Types**: Avoid combining different visualization types that serve distinct purposes, as it can confuse the audience.

The repository emphasizes the importance of thoughtful design in data visualization to enhance clarity and accuracy.
## Links

1. [Weissgerber et al., 2015, PLOS Biology](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128) - A publication discussing the limitations of bar graphs in scientific publications.
2. [Matand et al., 2020, BMC Plant Biology](https://link.springer.com/article/10.1186/s12870-020-2243-7) - A study that provides insights into multi-factorial experiments and their visual representation.
3. [Li et al., 2022, BioRxiv](https://www.biorxiv.org/content/10.1101/2022.07.04.498697v1) - A preprint discussing the importance of data visualization in omics research.
4. [viridis](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) - A color scale package that is colorblind-friendly and grey scale-safe, recommended for effective data visualization.
5. [data-to-viz blog post](https://www.data-to-viz.com/caveat/pie.html) - A blog post exploring the issues with pie charts and offering alternatives for better data representation.
## Topics

- [[topics/Library/R]]
- [[topics/Library/RStudio]]
- [[topics/Library/rmarkdown]]
- [[topics/Concept/Data Visualization Best Practices]]
- [[topics/Concept/Color Scales in Data Visualization]]