
<!-- README.md is generated from README.Rmd. Please edit that file -->

# urosconfpkg

[![Travis build
status](https://travis-ci.org/bernhard-da/urosconfpkg.svg?branch=master)](https://travis-ci.org/bernhard-da/urosconfpkg)
[![Codecov test
coverage](https://codecov.io/gh/bernhard-da/urosconfpkg/branch/master/graph/badge.svg)](https://codecov.io/gh/bernhard-da/urosconfpkg?branch=master)

The goal of `urosconfpkg` is serve as a boilerplate for a modern,
CI-capable R package.

## Installation

You can install the latest version of `urosconfpkg` with:

``` r
remotes::install_github("bernhard-da/urosconfpkg")
```

## Example

We want to greet everybody

``` r
urosconfpkg::greets("unknown user")
#> hi 'unknown user', the uros 2019 in bukarest is great!
#> the uros 2020 will take place in vienna :)
```
