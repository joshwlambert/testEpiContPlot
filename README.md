
# testEpiContPlot

<!-- badges: start -->
[![R-CMD-check](https://github.com/joshwlambert/testEpiContPlot/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/joshwlambert/testEpiContPlot/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of testEpiContPlot is to test the interactive plotting of epicontacts
on the web.

***Conclusion***: The `pkgdown: as_is: true` code in the vignette yaml is the reason the interactive {epicontacts} plots will not render correctly on the pkgdown website (see [the {pkgdown} site for info on `as_is`](https://pkgdown.r-lib.org/reference/build_articles.html#output-formats)). 

Without `pkgdown: as_is: true` the rendering engine will default to `rmarkdown::html_document()`, as such, the features such as cross-referencing and figure caption numbering from `bookdown::html_document2()` will be lost.

## Installation

You can install the development version of testEpiContPlot from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("joshwlambert/testEpiContPlot")
```
