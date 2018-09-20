
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sdmTMB

<!-- [![Travis build status](https://travis-ci.org/seananderson/sdmTMB.svg?branch=master)](https://travis-ci.org/seananderson/sdmTMB) -->

The goal of sdmTMB is to

  - Be useful for our purpose of fitting high resolution species
    distribution models of groundfish with spatiotemporal GLMMs and
    estimating range shift metrics. Possibly be useful for other
    applications.
  - Have an interface that will be familiar to people who have used
    packages such as glmmTMB, lmer, or mgcv. E.g. accept formulas, use a
    `predict()` method, and present options as clear named arguments.
  - Not fit the kitchen sink, but do what it does elegantly. I.e. be
    opinionated in what it does.
  - Wherever possible use modular C++ code.
  - Maintain clearly documented model code.
  - Adhere to tidyverse package standards where possible.

## Installation

You can install sdmTMB
with:

``` r
devtools::install_github("seananderson/sdmTMB") # won't work; still private
```

## Example

The main function is `sdmTMB()`. See `?sdmTMB` and `?predict.sdmTMB` for
the most complete examples.
