
# WeibullR.shiny

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/WeibullR.shiny)](https://CRAN.R-project.org/package=WeibullR.shiny)
![](http://cranlogs.r-pkg.org/badges/grand-total/WeibullR.shiny)
![](http://cranlogs.r-pkg.org/badges/WeibullR.shiny) [![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![DOI](https://zenodo.org/badge/641128069.svg)](https://zenodo.org/badge/latestdoi/641128069)
<!-- badges: end -->

<img src="https://github.com/paulgovan/WeibullR.shiny/blob/master/inst/app/www/WeibullR.png?raw=true" style="width:25.0%" />

A Shiny web application for life data analysis that depends on WeibullR,
an R package for Weibull analysis.

# Getting Started

To install WeibullR.shiny in R:

``` r
install.packages("WeibullR.shiny")
```

To install the development version:

``` r
devtools::install_github('paulgovan/weibullr.shiny')
```

To launch the app:

``` r
WeibullR.shiny::WeibullR.shiny()
```

Or to access the app through a browser, visit
[paulgovan.shinyapps.io/WeibullRshiny](paulgovan.shinyapps.io/WeibullRshiny).

# Example

## Landing

Launching the app brings up the Landing tab. From here you can access
this ReadMe, download an example dataset, or navigate to the Data tab.

![](https://github.com/paulgovan/WeibullR.shiny/blob/master/inst/images/Landing.png?raw=true)

## Data

For this example, we will use the example ‘Time-to-Failure’ dataset. To
access, first download the dataset locally from the Landing tab, and
then use the Data Input option in the Data tab to upload the dataset to
the app. At this point, your app should look like the image below. There
are additional options for arranging your data for analysis, but for
here we will use the default option.

![](https://github.com/paulgovan/WeibullR.shiny/blob/master/inst/images/Data.png?raw=true)

## Modeling

Now click on the Modeling tab to build the model. The app will use the
default options to build a Probability Plot. Feel free to try different
options to configure the model. Below the plot are additional plot
options to configure the plot.

![](https://github.com/paulgovan/WeibullR.shiny/blob/master/inst/images/ProbPlot.png?raw=true)

Finally, click on the Contour Plot tab to build a contour plot. As
before, there are other plot options for configuring the contour plot.

![](https://github.com/paulgovan/WeibullR.shiny/blob/master/inst/images/ContPlot.png?raw=true)

## More Resources

For more info on WeibullR.plotly, visit
[paulgovan.github.io/WeibullR.plotly/](https://paulgovan.github.io/WeibullR.plotly/)

For an interactive introduction to Life Data Analysis, check out
[WeibullR.learnr](https://paulgovan.github.io/WeibullR.learnr/)
