
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite2

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite2 is to manipulate a string in several ways.

## Installation

You can install the development version of regexcite2 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("corinabioinformatic/regexcite2")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite2)
## basic example code
```

For example run:

``` r
str_split_one("a,b,c", pattern=",")
#> [1] "a" "b" "c"
# Result: 
# c("a", "b", "c")
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
