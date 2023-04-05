R packages
================

This page provides an overview of my R packages and those I have
contributed to.

## Multivariate linear models

### heplots

[<img src='https://raw.githubusercontent.com/friendly/heplots/master/man/figures/logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/heplots)

Provides HE plot and other functions for visualizing hypothesis tests in
multivariate linear models. HE plots represent
sums-of-squares-and-products matrices for linear hypotheses and for
error using ellipses (in two dimensions) and ellipsoids (in three
dimensions). The related ‘candisc’ package provides visualizations in a
reduced-rank canonical discriminant space when there are more than a few
response variables.

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

### mvinfluence

[<img src='https://raw.githubusercontent.com/friendly/mvinfluence/master/man/figures/logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/mvinfluence)

Computes regression deletion diagnostics for multivariate linear models
and provides some associated diagnostic plots. The diagnostic measures
include hat-values (leverages), generalized Cook’s distance, and
generalized squared ‘studentized’ residuals. Several types of plots to
detect influential observations are provided.

### matlib

[<img src='https://raw.githubusercontent.com/friendly/matlib/master/matlib-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/matlib)

A collection of matrix functions for teaching and learning matrix linear
algebra as used in multivariate statistical methods. These functions are
mainly for tutorial purposes in learning matrix algebra ideas using R.
In some cases, functions are provided for concepts available elsewhere
in R, but where the function call or name is not obvious. In other
cases, functions are provided to show or demonstrate an algorithm. In
addition, a collection of functions are provided for drawing vector
diagrams in 2D and 3D.

### gellipsoid

[<img src='https://raw.githubusercontent.com/friendly/gellipsoid/master/man/figures/gellipsoid-logo.png' height='120' align='left' style="padding:'20px'">](https://github.com/friendly/gellipsoid)

Represent generalized geometric ellipsoids with the “(U,D)”
representation. It allows degenerate and/or unbounded ellipsoids,
together with methods for linear and duality transformations, and for
plotting. The ideas are described in Friendly, Monette & Fox (2013).

### two way
