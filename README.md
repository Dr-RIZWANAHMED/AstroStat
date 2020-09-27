# AstroStat
Astrostatistics lectures by prof. E. Feigelson (Penn State University) - Final Group Project

# Multivariate Analysis of Exoplanet Properties
Laboratory of Computational Physics @ Physics of Data, UniPD
Braghetto Anna, Frazzetto Paolo, Schimmenti Vincenzo Maria, Signor Theosamuele
## Assignment
This is a multistep exercise in exploring a multivariate dataset of random variables. Omit trial plots and tests, including only those with meaningful results. Some suggested R functions are given [in brackets]. Annotate the R script clearly, and provide an informal document with paragraph-length interpretation of important plots and tests. Students are encouraged to work in pairs.

a) Download dataset Obtain an ASCII multivariate dataset from The Extrasolar Planets Encyclopedia (http://exoplanet.eu/catalog.php (http://exoplanet.eu/catalog.php)). Select variables of interest of both the planet and host star … be generous, as extraneous variables can be omitted later. [names, dim, summary]

b) Univariate analysis Present the mass distribution of known exoplanets. Consider stratifying by discovery method (radial velocity vs. transits). Try making pretty overlapping histograms with unsaturated colors from the ColorBrewer palette. [boxplot, hist, density]

c) Bivariate analysis Examine the relationship between two interesting variables, perhaps semi-major vs. eccentricity or (for transiting planets) planet mass vs. planet radius. [plot, boxplot with cut or split, cor, scatter.smooth/kde2d/ supersmu/loess/ash, lm/residual analysis]

d) Prepare multivariate analysis Remove outliers and standardize variables. Add a new binary variable indicator for multiple planets. [boxplot, pairs, is.na. scale, cbind]

e) Multivariate analysis Search for linear and nonlinear structure among the transiting planets. Reduce dimensionality: remove variables of no apparent interest, and create new linear combinations of variables. Choose a response variable for multiple regression. [princomp and plots, lm/plots, earth]

f) Machine learning Try some modern methods for nonlinear dimensionality reduction and visualization such as Self-Organizing Maps, Isomap, diffusion maps, Local Linear Embedding, Stochastic Neighborhood Embedding. CRAN packages kohonen, dimRed, diffusionMap, etc.
