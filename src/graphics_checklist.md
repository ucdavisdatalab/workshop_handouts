Graphics Checklist
==================

First, make sure you've chosen an appropriate graphic. The table below
has *suggestions*. Sometimes other graphics may be more appropriate.

First Feature | Second Feature | Plot
------------- | -------------- | ----
categorical   |                | bar, dot
categorical   | categorical    | bar, dot, mosaic
numerical     |                | box, density, histogram
numerical     | categorical    | box, density
numerical     | numerical      | line, scatter, smooth scatter

Next, go through this checklist with each graphic you plan to use:

* [ ] **Does the graphic convey important information?** Don't include graphics
  that are uninformative or redundant.

* [ ] **Title?** Make sure the title explains what the graphic shows.

* [ ] **Axis labels?** Label the axes in plain language (no variable names!).

* [ ] **Axis units?** Label the axes with units (inches, dollars, etc).

* [ ] **Legend?** Any graphic that shows two or more categories coded by style
  or color must include a legend.

* [ ] **Appropriate scales and limits?** Make sure the scales and limits of the
  axes do not lead people to incorrect conclusions. For side-by-side graphics
  or graphics that viewers will compare, use identical scales and limits.

* [ ] **No overplotting?** Scatter plots where many plot points overlap hide
  the actual patterns in the data. Make the points smaller or use a
  two-dimensional density plot (a smooth scatter plot) instead.

* [ ] **No more than 5 lines?** Line plots with more than 5 lines risk becoming
  hard-to-read "spaghetti" plots. Generally a line plot with more than 5 lines
  should be split into multiple plots with fewer lines. If the x-axis is
  discrete, consider using a heat map instead.

* [ ] **Should it be a dot plot?** Pie plots are hard to read and bar plots
  don't use space efficiently [@cleveland90; @heer10]. Generally a dot plot is
  a better choice.

* [ ] **Print safe?** Design graphics to be legible in black & white. Color is
  great, but use point and line styles to distinguish groups in addition to
  color. Also try to choose colors that are accessible to colorblind people.
  The `RColorBrewer`{.text} and `viridis`{.text} packages can help with
  choosing colors.
