
[![Travis build status](https://travis-ci.org/nfox29/photosearcher.svg?branch=master)](https://travis-ci.org/nfox29/photosearcher) <!-- README.md is generated from README.Rmd. Please edit that file -->

photosearcher
=============

The goal of photosearcher is to provide a repeatable methodology for accessing the Flickr API.

Installation
------------

You can install the released version of photosearcher from github with:

``` r
devtools::install_github("nfox29/photosearcher")
```

Example
-------

This is a basic example of the main photo\_search function:

``` r
## photo_search(min_taken = "2019-01-01",
##              max_taken = "2019-01-02",
##              text = "tree",
##              bbox = "-13.623047,47.279229,3.251953,60.630102",
##              has_geo = TRUE)
```
