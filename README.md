
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `reprscidemoproj`

<!-- badges: start -->
<!-- badges: end -->

The goal of `reprscidemoproj` is to demonstrate a reproducible data
analysis project.

## Docker

Run this project in Docker

    docker pull xmjandrews/verse:20.06.25
    docker run --rm -p 8787:8787 -e PASSWORD=<passwd> -e ROOT=true -v <local drive>:/home/rstudio xmjandrews/verse:20.06.25

The `Dockerfile` for this Docker image is also available
[here](Dockerfile).

## Package

``` r
library(bayeslmm)
lmmplot(sleepstudy)
```
