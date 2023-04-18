---
geometry: margin=1in
header-includes:
  - \pagenumbering{gobble}
---

![](https://datalab.ucdavis.edu/wp-content/uploads/2019/07/datalab-logo-full-color-rgb-1.png){width=25%}

Data Visualization Guidelines
=============================

Choosing a Plot Type
--------------------

First, make sure you've chosen an appropriate plot type. The table below has
*suggestions*. Sometimes other plot types may be more appropriate.

First Feature | Second Feature | Plot
------------- | -------------- | ----
categorical   |                | bar, dot
categorical   | categorical    | bar, dot, mosaic
numerical     |                | box, density, histogram
numerical     | categorical    | box, density
numerical     | numerical      | line, scatter, heatmap

For three or more features, use point shapes, line styles, colors, or facets. 


Checklist
---------

Next, go through this checklist with each visualization you plan to use for
communications:

* [ ] **Does the visualization present a finding?** Don't include plots that
  are uninformative or redundant.

* [ ] **Title?** Make sure the title explains what the visualization shows.

* [ ] **Axis labels?** Label the axes in plain language (no variable names!).

* [ ] **Axis units?** Label the axes with units (inches, dollars, etc).

* [ ] **Legend?** Any plot that shows two or more groups coded by style or
  color must include a legend.

* [ ] **Appropriate scales and limits?** Make sure the scales and limits of the
  axes do not lead people to incorrect conclusions. For side-by-side plots or
  plots that viewers will compare, use identical scales and limits.

* [ ] **Is the data hiding the message?** Sometimes using a *faithful* sample
  is more revealing than all of the data. In scatter plots, overlapping points
  can hide patterns in the data. Take a sample, make the points smaller, or use
  a two-dimensional density plot (a smooth scatter plot) instead.

* [ ] **Are there too many details on the plot?** A plot with too many details
  can be overwhelming and obscure the story the data is trying to tell. If a
  plot shows more than 5 groups, consider whether there's a sensible way to use
  faceting to break the plot into multiple subplots.

* [ ] **Does it use geometry efficiently?** Carefully consider whether the
  basic graphical elements of each plot match the data type and use space
  efficiently. For example, pie plots are hard to read. Generally a dot plot is
  a better choice.

* [ ] **Accessible and print safe?** Design visualizations to be legible to a
  diverse audience. Use point, line, and fill styles to distinguish groups in
  addition to color so that visualizations are accessible to colorblind people.
  Also consider whether people will print your visualization in black and
  white. The `RColorBrewer`{.text} and `viridis`{.text} packages can help with
  choosing colors.
