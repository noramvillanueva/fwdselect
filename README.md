# FWDselect: Selecting Variables in Regression Models

[![CRAN Downloads](https://cranlogs.r-pkg.org/badges/grand-total/FWDselect)](https://cran.r-project.org/package=FWDselect)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/FWDselect)](https://cran.r-project.org/package=FWDselect)
[![CRAN Downloads](https://cranlogs.r-pkg.org/badges/last-month/FWDselect?color=ff69b4)](https://cran.r-project.org/package=FWDselect)

```FWDselect``` is an R package for selecting the best subset of variables (or best model) using different types of data (binary, Gaussian or Poisson) and applying it in different contexts (parametric or non-parametric). 
In many practical situations, when there are a large number (p) of input variables 
(i.e., features or explanatory variables) which may or may not be relevant for predicting the response,
it is useful to be able to reduce the model. It is desirable to reduce the number of input variables 
to both redues the computational cost of  modeling and, in some cases, to improve the performance of the model. 

In addition, a parametric model (allometric model) can be estimated. 
Particularly, the package  provides facilities for fast smoothness
estimation, and the calculation of their first and second derivative. Users can 
define the smoothers parameters. Confidence intervals calculation is provided 
by bootstrap methods. Binning techniques were applied to speed up computation 
in the estimation and testing processes.

## Installation
```FWDselect``` is available through both CRAN and GitHub.

Get the released version from CRAN:
```
install.packages("FWDselect")
```

Or the development version from GitHub:
```
# install.packages("devtools")
devtools::install_github("sestelo/FWDselect")
```
