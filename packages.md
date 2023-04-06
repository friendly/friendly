R packages
================

This page provides overview descriptions of my R packages and those I
have contributed to. The hex icons link to the GitHub repositories.
Links to the package **Documentation** are also provided.

Topics: [Multivariate linear models](#MLM) \|\| [Categorical data
analysis](#CDA) \|\| [Data](#DATA)

## Multivariate linear models

### heplots

[<img src='https://raw.githubusercontent.com/friendly/heplots/master/man/figures/logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/heplots)

Provides HE plot and other functions for visualizing hypothesis tests in
multivariate linear models. HE plots represent
sums-of-squares-and-products matrices for linear hypotheses and for
error using ellipses (in two dimensions) and ellipsoids (in three
dimensions). The related ‘candisc’ package provides visualizations in a
reduced-rank canonical discriminant space when there are more than a few
response variables. **Documentation**:
[friendly.github.io/heplots](http://friendly.github.io/heplots/)

### candisc

[<img src='https://raw.githubusercontent.com/friendly/candisc/master/candisc-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/candisc)

Functions for computing and visualizing generalized canonical
discriminant analyses and canonical correlation analysis for a
multivariate linear model. Traditional canonical discriminant analysis
is restricted to a one-way ‘MANOVA’ design and is equivalent to
canonical correlation analysis between a set of quantitative response
variables and a set of dummy variables coded from the factor variable.
The ‘candisc’ package generalizes this to higher-way ‘MANOVA’ designs
for all factors in a multivariate linear model, computing canonical
scores and vectors for each term. The graphic functions provide low-rank
(1D, 2D, 3D) visualizations of terms in an ‘mlm’ via the ‘plot.candisc’
and ‘heplot.candisc’ methods. Related plots are now provided for
canonical correlation analysis when all predictors are quantitative.
**Documentation**:
[friendly.github.io/candisc](https://friendly.github.io/candisc/)

### mvinfluence

[<img src='https://raw.githubusercontent.com/friendly/mvinfluence/master/man/figures/logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/mvinfluence)

Computes regression deletion diagnostics for multivariate linear models
and provides some associated diagnostic plots. The diagnostic measures
include hat-values (leverages), generalized Cook’s distance, and
generalized squared ‘studentized’ residuals. Several types of plots to
detect influential observations are provided. **Documentation**:
[friendly.github.io/mvinfluence](https://friendly.github.io/mvinfluence/)

### matlib

[<img src='https://raw.githubusercontent.com/friendly/matlib/master/matlib-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/matlib)

A collection of matrix functions for teaching and learning matrix linear
algebra as used in multivariate statistical methods. These functions are
mainly for tutorial purposes in learning matrix algebra ideas using R.
In some cases, functions are provided for concepts available elsewhere
in R, but where the function call or name is not obvious. In other
cases, functions are provided to show or demonstrate an algorithm. In
addition, a collection of functions are provided for drawing vector
diagrams in 2D and 3D. **Documentation**:
[friendly.github.io/matlib](https://friendly.github.io/matlib/)

### gellipsoid

[<img src='https://raw.githubusercontent.com/friendly/gellipsoid/master/man/figures/gellipsoid-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/gellipsoid)

Represent generalized geometric ellipsoids with the “(U,D)”
representation. It allows degenerate and/or unbounded ellipsoids,
together with methods for linear and duality transformations, and for
plotting. The ideas are described in Friendly, Monette & Fox (2013).
<br/>

### two way

[<img src='https://raw.githubusercontent.com/friendly/twoway/master/twoway-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/twoway)
Carries out analyses of two-way tables with one observation per cell,
together with graphical displays for an additive fit and a diagnostic
plot for removable ‘non-additivity’ via a power transformation of the
response. It implements Tukey’s Exploratory Data Analysis (1973) \<ISBN:
978-0201076165\> methods, including a 1-degree-of-freedom test for
row\*column ‘non-additivity’, linear in the row and column effects.
**Documentation**: [rdrr.io/cran/twoway/](https://rdrr.io/cran/twoway/)

## Categorical data analysis

### vcdExtra

[<img src='https://raw.githubusercontent.com/friendly/vcdExtra/master/man/figures/logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/vcdExtra)
Provides additional data sets, methods and documentation to complement
the ‘vcd’ package for Visualizing Categorical Data and the ‘gnm’ package
for Generalized Nonlinear Models. In particular, ‘vcdExtra’ extends
mosaic, assoc and sieve plots from ‘vcd’ to handle ‘glm()’ and ‘gnm()’
models and adds a 3D version in ‘mosaic3d’. Additionally, methods are
provided for comparing and visualizing lists of ‘glm’ and ‘loglm’
objects. This package is now a support package for the book, “Discrete
Data Analysis with R” by Michael Friendly and David Meyer.
**Documentation**:
[friendly.github.io/vcdExtra](http://friendly.github.io/vcdExtra/)

## Data

### HistData

[<img src='https://raw.githubusercontent.com/friendly/HistData/master/man/figures/HistData-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/HistData)
The ‘HistData’ package provides a collection of small data sets that are
interesting and important in the history of statistics and data
visualization. The goal of the package is to make these available, both
for instructional use and for historical research. Some of these present
interesting challenges for graphics or analysis in R. **Documentation**:
[rdrr.io/cran/HistData/](https://rdrr.io/cran/HistData/)

### Guerry

[<img src='https://raw.githubusercontent.com/friendly/Guerry/master/man/figures/Guerry-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/Guerry)
Maps of France in 1830, multivariate datasets from A.-M. Guerry and
others, and statistical and graphic methods related to Guerry’s “Moral
Statistics of France”. The goal is to facilitate the exploration and
development of statistical and graphic methods for multivariate data in
a geospatial context of historical interest. **Documentation**:
[rdrr.io/cran/Guerry/](https://rdrr.io/cran/Guerry/)

### Lahman

[<img src='https://raw.githubusercontent.com/cdalzell/Lahman/master/man/figures/Lahman_hex.png' height='120' align='left' style="padding:'20px'">](https://github.com/cdalzell/Lahman)
Provides the tables from the ‘Sean Lahman Baseball Database’ as a set of
R data.frames. It uses the data on pitching, hitting and fielding
performance and other tables from 1871 through 2021, as recorded in the
2022 version of the database. Documentation examples show how many
baseball questions can be investigated. **Documentation**:
[rdrr.io/cran/Lahman/](https://rdrr.io/cran/Lahman/)

### statquotes

[<img src='https://raw.githubusercontent.com/friendly/statquotes/master/man/figures/statquotes-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/statquotes)
Generates a random quotation from a data base of quotes on topics in
statistics, data visualization and science. Other functions allow
searching the quotes database by key term tags, or authors or creating a
word cloud. **Documentation**:
[rdrr.io/cran/statquotes/](https://rdrr.io/cran/statquotes/)
