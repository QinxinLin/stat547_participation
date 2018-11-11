
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pp

This is an R package that gives `sqrt()` friends by providing other
power functions.

## Installation

You can install the released version of pp from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("devtools")
devtools::install_github("QinxinLin/pp")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
pp::reciprocal(2)
#> [1] 0.5
```

## For Developers

(Again, I don’t actually intend for anyone to develop this silly
package, but if I did, here’s what I’d write.)

Use the internal `pow` function as the machinery for the front-end
functions such as `square`, `cube`, and `reciprocal`.
