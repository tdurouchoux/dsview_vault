---
already_read: false
link: https://github.com/cxli233/FriendsDontLetFriends
read_priority: 1
relevance: 0
source: null
tags:
- Data_Visualization
type: Content
upload_date: '2024-01-25'
---

https://github.com/cxli233/FriendsDontLetFriends
## Summary

The content is an opinionated essay on good and bad practices in data visualization, with examples and explanations. Here are the main points:

1. **Bar Plots for Mean Separation**: Avoid using bar plots for mean separation as they can be misleading. Check data distributions before using them.
2. **Violin Plots for Small Sample Sizes**: Violin plots are ineffective for small sample sizes (n < 50) as distributions and quartiles vary widely.
3. **Bidirectional Color Scales**: Avoid using bidirectional color scales for unidirectional data. The darkest and lightest colors should represent meaningful values.
4. **Bar Plot Meadows**: Bar plot meadows are ineffective for multi-factorial experiments. Thoughtful designs regarding grouping/faceting are required.
5. **Heatmaps**: Reorder rows and columns for effective heatmaps. Check for outliers and consider data range at each factor level.
6. **Network Graphs**: Try different layouts for network graphs to ensure they are effective and easy to interpret.
7. **Position vs. Length-based Visualizations**: Avoid confusing position-based and length-based visualizations. Be cautious with bar plots with broken axis.
8. **Pie Charts and Concentric Donuts**: Pie charts and concentric donuts are ineffective for comparing data. Use stacked bar plots instead.
9. **Color Scales**: Avoid red/green and rainbow color scales. Use colorblind-friendly and grayscale-safe color scales like viridis.
10. **Stacked Bar Plots**: Reorder stacked bar plots for better visualization. Avoid mixing stacked bars and mean separation plots.
11. **Histograms for Small Sample Sizes**: Histograms are not robust for small sample sizes. Plot all data points for small samples.
12. **Boxplots for Bimodal Data**: Boxplots cannot handle bimodal data. Plot all data points for small to moderate sample sizes.

The content also includes R scripts to generate the graphics and tutorials on how to improve certain types of visualizations.
## Links

- [Heatmap Tutorial](https://github.com/cxli233/FriendsDontLetFriends/blob/main/Heatmap_tutorial.md) : A tutorial on how to reorder rows and columns of a heatmap to improve data visualization.
- [Publication on Bar Graph Limitations](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128) : A publication discussing the limitations of bar graphs in data visualization.
- [Viridis Color Scales](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) : An introduction to viridis color scales, which are colorblind-friendly and grey scale-safe.

## Topics

![](topics/Concept/Data%20Visualization)

![](topics/Concept/Heatmap)

![](topics/Concept/Network%20Graph)

![](topics/Concept/Bar%20Plot)

![](topics/Concept/Violin%20Plot)