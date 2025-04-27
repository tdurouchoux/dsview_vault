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

The repository "Friends Don't Let Friends" critiques various poor data visualization practices and their implications. Key points include:

1. **Bar Plots for Mean Separation**: Avoid using simple bar plots for comparing means without addressing underlying distributions.
2. **Violin Plots for Small Sample Sizes**: Use of these plots is misleading when sample sizes are low.
3. **Bidirectional Color Scales**: Not suitable for unidirectional data.
4. **Bar Plot Meadows**: Ineffective for multi-factorial data unless well-designed.
5. **Heatmaps**: Should always consider reordering rows and columns for clarity and check for outliers.
6. **Neglecting Data Range**: Checking range at each factor level is essential to avoid skewed interpretations.
7. **Network Graphs**: Experimenting with layout is crucial for effective communication of relationships.
8. **Position vs. Length in Visualizations**: Confusion can arise from misusing these representations.
9. **Pie Charts**: Generally ineffective; consider using stacked bars instead.
10. **Concentric Donuts**: Misleading; better to use simpler visualizations.
11. **Color Scales**: Avoid those that are colorblind-unfriendly or don't print well.
12. **Stacked Bar Plots**: Require careful optimization for ordering to convey data effectively.
13. **Combining Different Visualization Types**: Mixing stacked bars with mean separation confuses distinct data visualization tasks.
14. **Histograms for Small Samples**: Often misleading due to sensitivity to bin sizes; raw data representation is preferred.
15. **Boxplots for Bimodal Data**: Ineffective; alternative representations of the data distribution should be considered.

The repository emphasizes that these visualization choices can significantly impact data interpretation and should be approached with caution.
## Links

- [Understanding Pie Charts and Their Alternatives](https://www.data-to-viz.com/caveat/pie.html) : Explains the limitations of pie charts and offers alternative visualization methods for representing fractional data.
- [Viridis Color Scale Documentation](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) : Documentation for the Viridis color scales, which are colorblind-friendly and suitable for grey scale representation.
- [PLOS Biology Article on Visualization](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128) : A study highlighting the issues with common visualization practices in scientific literature.
- [The Importance of Checking Data Range at Each Factor Level](https://github.com/cxli233/FriendsDontLetFriends#7-friends-dont-let-friends-forget-to-check-data-range-at-each-factor-level) : An illustrative section on ensuring proper data range checks for multifactorial experiments in visualizations.
- [Network Layout Visualization Examples](https://github.com/cxli233/FriendsDontLetFriends/blob/main/Results/Different_layouts.png) : A comparison of various layout options for network graphs to illustrate differences in appearance and interpretation.

## Topics

![](topics/Concept/Data%20Visualization%20Best%20Practices)

![](topics/Tool/R)

![](topics/Library/ggplot2)

![](topics/Concept/Outlier%20Detection%20in%20Visualization)

![](topics/Concept/Multifactorial%20Experiment%20Design)

![](topics/Concept/Network%20Graph%20Visualization)

![](topics/Concept/Effective%20Use%20of%20Color%20in%20Visualizations)

![](topics/Concept/Choosing%20the%20Right%20Graph%20Type)