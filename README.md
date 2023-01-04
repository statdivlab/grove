------------------------------------------------------------------------

<!-- badges: start -->

[![R-CMD-check](https://github.com/statdivlab/groves/workflows/R-CMD-check/badge.svg)](https://github.com/statdivlab/groves/actions) [![codecov.io](https://codecov.io/gh/statdivlab/groves/coverage.svg?branch=main)](https://codecov.io/gh/statdivlab/groves?branch=main) <!-- badges: end -->

<span style="font-family:Arial; font-size:2em;"> **G**ene t**R**ee **O**rdination **V**isualization for **E**xploration**S**</span>

`groves` is an `R` package for visualizing a set of gene-level phylogenies.

## About

If you are studying microbial evolution, you will often make a phylogenomic tree (typically using concatenation of gene-level alignments) to summarize the evolutionary relationships between a set of genomes. However, genes that are subject to different evolutionary pressures can have distinct evolutionary histories. For this reason, it can be useful to investigate gene-level phylogenetic trees in addition to genome-level phylogenomic trees.

This package provides a visualization method to compare a set of gene-level trees and a phylogenomic tree. Specifically, it will produce a two-dimensional scatterplot, in which each point represents a tree, that preserves as much variation between the trees as possible. This can be used to identify genes with outlying evolutionary histories, compare sets of genes, or even highlight anomalies in the phylogenomic preprocessing process. This visualization can be produced from functions in this R package (see the [vignette](https://github.com/statdivlab/groves/blob/main/vignettes/introduction_to_groves.Rmd) for an example) or from a shiny app (run the functions `groves::run_shiny()`).

## Installation

`groves` is available through GitHub and can be installed with the following.

    if (!require("remotes", quietly = TRUE))
        install.packages("remotes") # check that remotes is installed
    remotes::install_github("statdivlab/groves") 
    library(groves)

## Usage

This package is still in development. Vignettes are coming soon, with instructions and examples of how to use `groves` to analysis your gene trees.

## Issues/Requests

If you have any issues using our software or further questions please submit an issue [here](https://github.com/statdivlab/groves/issues).
