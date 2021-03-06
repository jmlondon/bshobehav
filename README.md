<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Last-changedate](https://img.shields.io/badge/last%20change-2019--04--09-green.svg)](https://github.com/jmlondon/buckshot/commits/master)
[![minimal R
version](https://img.shields.io/badge/R%3E%3D-3.5.3-green.svg)](https://cran.r-project.org/)
[![ORCiD](https://img.shields.io/badge/ORCiD-0000--0002--3647--5046-green.svg)](http://orcid.org/0000-0002-3647-5046)

buckshot: Research compendium in support of the manuscript “Haul-out behavior and detectability of bearded, ribbon, and spotted seals in the Bering and Chukchi Seas”
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Compendium DOI:

This is published to Zenodo.

[![DOI](https://zenodo.org/badge/134605799.svg)](https://zenodo.org/badge/latestdoi/134605799)

The files hosted at github.com/jmlondon/buckshot are the development
versions and are likely to change

### Authors of this repository:

Josh M. London
(<a href="mailto:josh.london@noaa.gov" class="email">josh.london@noaa.gov</a>)
Paul Conn
(<a href="mailto:paul.conn@noaa.gov" class="email">paul.conn@noaa.gov</a>)

### Publication status:

This compendium and the associated manuscript are intended for
submission to a scientific publication

### Overview of contents

This repository is our research compendium for our analysis of the
haul-out behavior and detectability of bearded, ribbon, and spotted
seals in the Bering and Chukchi seas. We intend for this compendium to
containa all data, code, and text associated with the publication. The
`R` files in the `analysis/` directory contain details of how all the
analyses reported in the paper were conducted. The `data/` directory
contains all the R data objects and `data-raw/` contains original data
files or database exports. The `manuscript/` diretory currently contains
the \_*.docs* versions of the manuscript.

### The R package

This repository is organized as an R package. There are no actual R
functions in this package - all the R code is in the Rmd file. We simply
used the R package structure to help manage dependencies, to take
advantage of organizational and build features.
