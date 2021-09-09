
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start 
[![CRAN status](https://www.r-pkg.org/badges/version/corncob)](https://CRAN.R-project.org/package=corncob)-->

[![R-CMD-check](https://github.com/statdivlab/rigr/workflows/R-CMD-check/badge.svg)](https://github.com/statdivlab/rigr/actions)
[![codecov](https://codecov.io/gh/statdivlab/rigr/branch/main/graph/badge.svg)](https://codecov.io/gh/statdivlab/rigr)
<!-- badges: end -->

# `rigr`: Regression, Inference, and General Data Analysis Tools for R

# Introduction

`rigr` is a R package designed to facilitate easy adoption of regression
and inference tools in R. `rigr`, formerly known as `uwIntroStats`,
compiles output from existing routines together in an intuitive format,
and adds functionality to existing functions. For instance, the
`regress` function can perform linear models and generalized linear
models. The user can also specify multiple-partial F-tests to print out
with the model coefficients, and robust standard errors are provided
automatically. We also provide functions for descriptive statistics and
one- and two-sample inference with improved, legible output.

## Installation

You can install `rigr` from CRAN using the code below.

    install.packages("rigr")

You can install the development version of `rigr` from GitHub using the
code below.

    devtools::install_github("statdivlab/rigr")

`rigr` is maintained by the
[StatDivLab](http://statisticaldiversitylab.com/), but relies on
community support to log issues and implement new features. Is there a
method you would like to have implemented? Please submit a pull request
or start a
[discussion](https://github.com/statdivlab/rigr/discussions/)!

## Documentation

Examples of how to use the main functions in `rigr` are provided in
three vignettes. One details the `regress` function and its utilities,
one details the `descrip` function for descriptive statistics, and the
third details functions used for one- and two-sample inference,
including `ttest`, `wilcoxon`, and `proptest`.

## Humans

Maintainer: [Amy Willis](http://statisticaldiversitylab.com/)

Authors: [Scott S Emerson](http://www.emersonstatistics.com/), [Andrew J
Spieker](https://www.vumc.org/biostatistics/person/andrew-spieker-phd/),
[Brian D Williamson](https://bdwilliamson.github.io/), [Travis Y Hee
Wai](https://scholar.google.com/citations?user=WaJn2wIAAAAJ&hl=en/),
Solomon Lim, [Charles Wolock](https://cwolock.github.io/), and [Taylor
Okonek](https://taylorokonek.github.io/).

## Issues

If you encounter any bugs, please [file an
issue](https://github.com/statdivlab/rigr/issues/). Better yet, [submit
a pull request](https://github.com/statdivlab/rigr/pulls/)!

Do you have a question? Please first check out the vignettes, then
please post on the
[Discussions](https://github.com/statdivlab/rigr/discussions/).
