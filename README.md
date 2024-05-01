
# templateRepository

<!-- badges: start -->
[![R-CMD-check](https://github.com/myles-mitchell/templateRepository/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/myles-mitchell/templateRepository/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of templateRepository is to provide template files for setting up a
GitHub repository, including:

* README.md with information about the package and clear usage instructions
* R package skeleton set up using `devtools::create()`
* tests/ folder initialised with `usethis::use_test()`
* GitHub Actions templates set up with `usethis::use_github_action()`
* Pre-commit hooks set up with {precommit} package

## Related projects

This project depends on the R packages listed in the DESCRIPTION file. It also
relies on the upstream repositories at ...

The following downstream repositories depend on this package ...

## Installation

You can install the development version of templateRepository from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("myles-mitchell/templateRepository")
```

## Overview

The add.R script contains a function `add(a, b)` which takes two numerical
arguments and adds them together.

## Usage

This is a basic example which shows you how to solve a common problem:

``` r
library(templateRepository)
add(2, 3)
```

## Tests

To run the tests, open the package in RStudio and hit Ctrl+Shift+T.
Alternatively you can run `devtools::test()`.
