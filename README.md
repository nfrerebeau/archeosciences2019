
<!-- README.md is generated from README.Rmd. Please edit that file -->

# TaphoCeram

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2613512.svg)](https://doi.org/10.5281/zenodo.2613512)
[![GitHub
Release](https://img.shields.io/github/release/nfrerebeau/TaphoCeram.svg)](https://github.com/nfrerebeau/TaphoCeram/releases)
[![Travis-CI Build
Status](https://travis-ci.org/nfrerebeau/TaphoCeram.svg?branch=master)](https://travis-ci.org/nfrerebeau/TaphoCeram)

This repository contains the data and code for our paper (in french):

> Frerebeau, N., Ben Amara, A. et Cantin, N. (2020). Analyse de données
> de composition et identification des altérations géochimiques des
> matériaux céramiques : le cas des productions d’un atelier ibérique
> (Teruel, Espagne ; IIe-Ier millénaire avant J.-C.). *Archéosciences,
> revue d’Archéométrie*, X, p. X-X. DOI : <https://doi.org/xxx/xxx>.

The files hosted in this repository are the development versions and may
have changed since the paper was published.

## How to cite

Please cite this compendium as:

> Frerebeau, N., Ben Amara, A. and Cantin, N. (2020). *Compendium of R
> code and data for “Analyse de données de composition et identification
> des altérations géochimiques des matériaux céramiques : le cas des
> productions d’un atelier ibérique (Teruel, Espagne ; IIe-Ier
> millénaire avant J.-C.)”*. Accessed 26 avril 2020. Online at
> <https://doi.org/10.5281/zenodo.2613512>.

## Licenses

**Text and figures:**
[CC-BY-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/).

**Code:** see the [DESCRIPTION](DESCRIPTION) file.

**Datasets:**
[CC-BY-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/).

## How to download or install

You can download the compendium as a zip from from this
[URL](http://github.com/nfrerebeau/TaphoCeram/archive/master.zip).

Or you can install this compendium as an R package, `TaphoCeram`, from
GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("nfrerebeau/TaphoCeram")
```

To download the package source as you see it on GitHub, for offline
browsing, use this line at the shell prompt (assuming you have Git
installed on your computer):

``` sh
git clone https://github.com/nfrerebeau/TaphoCeram.git
```

## Usage

Once the download is complete, open the `TaphoCeram.Rproj` in RStudio to
begin working with the package and compendium files.

The `analysis/` directory contains:

  - The Rmarkdown source file of the manuscript (in the `paper/`
    subdirectory),
  - All the figures generated from R code (in the `figures/`
    subdirectory),
  - All the raw data files (in CSV format, in the `data/` subdirectory),
  - Code files used for data cleaning (in the `scripts/` subdirectory).

The `R/` directory contains the custom R functions used in this project.
Datasets (in RDA format) are located in the `data/` directory.

## Dependencies

The original manuscript was produced with R 3.6.3. See the
[DESCRIPTION](DESCRIPTION) file for a full list of the packages that
this project depends on, including the suggested packages. The
`packrat/` directory contains the source code for all the packages we
depend on. If all works well, these will be installed on your machine
when you open `TaphoCeram.Rproj` in RStudio.
