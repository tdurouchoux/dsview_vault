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

The content is an opinionated essay on good and bad practices in data visualization, authored by Chenxin Li, Ph.D. It provides examples and explanations of common data visualization mistakes and offers better alternatives. The essay is structured into several sections, each addressing a specific type of visualization issue:

1. **Bar Plots for Mean Separation**: Avoid using bar plots for mean separation as they can be misleading. Instead, consider other visualizations that better represent the data distribution.
2. **Violin Plots for Small Sample Sizes**: Violin plots are ineffective for small sample sizes because the distributions and quartiles can vary widely.
3. **Bidirectional Color Scales for Unidirectional Data**: Avoid using bidirectional color scales for unidirectional data. The darkest and lightest colors should have meaningful representations.
4. **Bar Plot Meadows**: Bar plot meadows are ineffective for communicating results of multi-factorial experiments. Thoughtful designs regarding grouping/faceting by factors of interest are necessary.
5. **Heatmaps without Reordering Rows & Columns**: Heatmaps should consider reordering rows and columns to be effective. Clustering or other methods can help in reordering.
6. **Heatmaps without Checking Outliers**: Outliers in heatmaps can change how we perceive and interpret the visualization. Always check for outliers.
7. **Forgetting to Check Data Range at Each Factor Level**: In multifactor experiments, the range of the response variable can change widely between different factor levels. Always check the data range.
8. **Network Graphs without Trying Different Layouts**: The appearance of network graphs can make a huge difference in determining if they are effective. Try different layouts to find the most effective one.
9. **Confusing Position-based Visualizations with Length-based Visualizations**: Be careful not to confuse position-based visualizations (like dot and line plots) with length-based visualizations (like bar plots).
10. **Pie Charts**: Pie charts are criticized because humans are worse at reading angles and areas than lengths. Consider using stacked bar plots instead.
11. **Concentric Donuts**: Concentric donuts can be misleading because the arc lengths on the outer rings are much longer than those in the inner rings. Unwrap the donuts and use stacked bar plots.
12. **Red/Green and Rainbow Color Scales**: Avoid using red/green and rainbow color scales as they are not colorblind-friendly and do not preserve information well when printed in black and white. Use modern color scales like viridis.
13. **Forgetting to Reorder Stacked Bar Plots**: Stacked bar plots need to be optimized by grouping and ordering samples to be effective.
14. **Mixing Stacked Bars and Mean Separation**: Avoid mixing stacked bar plots and mean separation plots as they serve distinct tasks in data visualization.
15. **Using Histograms for Small Sample Sizes**: Histograms are not robust to bin numbers for small sample sizes. Graph all data points for small sample sizes.
16. **Using Boxplots for Bimodal Data**: Boxplots cannot handle bimodal data. Plot all data points using geom_quasirandom() from the ggbeeswarm package for small to moderate sample sizes.

The essay concludes by encouraging readers to stay tuned for more examples and updates. The content is accompanied by R scripts that generate the graphics shown in the essay, requiring R, RStudio, and the rmarkdown package.
## Links

- [R Download](https://cran.r-project.org/bin/) : R is a programming language and environment for statistical computing and graphics. It is widely used by statisticians, data analysts, and data scientists for data manipulation, calculation, and graphical display.
- [RStudio Download](https://www.rstudio.com/products/rstudio/download/) : RStudio is an integrated development environment (IDE) for R. It includes a console, syntax-highlighting editor that supports direct code execution, and a variety of robust tools.
- [ggbeeswarm](https://github.com/eclarke/ggbeeswarm) : ggbeeswarm is an extension to ggplot2 for creating bee swarm plots, which are a one-dimensional representation of data where points do not overlap.
- [Viridis Color Scales](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) : Viridis is a color scale that is both colorblind-friendly and grey scale-safe. It is often used as an alternative to rainbow color scales.
- [PLOS Biology Article on Bar Graphs](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128) : This article discusses the limitations of bar graphs and provides insights into better practices for data visualization.

## Topics

![[topics/Concept/Graphs)]]

![[topics/Concept/Heatmap)]]

![[topics/Concept/Data Visualization)]]