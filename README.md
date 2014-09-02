rtdists: Response time distributions in R
====

## Features

* uses fast-dm C code by Andreas Voss

## Installation

* From CRAN: In the future

* Development version from Github:  
Note, for installing the development version package `devtools` is needed which may require some additional software (see [here](http://r-pkgs.had.co.nz/intro.html) section "Getting started")
```
devtools::install_github("rtdists",user="rtdists")
```

## Get Started:
```
rrd(10, a=1, z=0.5, v=2, t0=0.5, d=0, sz=0, sv=0, st0=0)
rrd(10, parameters = c(1, 0.5, 2, 0.5, 0, 0, 0, 0))

example(diffusion)
```
