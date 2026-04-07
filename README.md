# Microbial community analysis and visualisation scripts

This repository contains the code used to process, analyse, and visualise data for the associated 
*Not all children are the same: Differences in the microbiome assembly during early development of seaweeds* 

## Overview

The scripts implement the full analysis workflow, including data preprocessing, statistical analyses, and figure generation. All analyses were conducted in R.

## Repository structure

* `data/` – input data (raw or processed) - to add after the paper is accepted
* `scripts/` – R scripts used for analysis
* `figures/` – output figures generated from the analyses - to add after the paper is accepted

## Workflow

Scripts are intended to be run in the following order:

1. `data_cleaning.R` – data import and preprocessing
2. `analysis.R` – statistical analyses
3. `figures.R` – figure generation

## Requirements

* R (version ≥ 4.0 recommended)
* Required packages may include: `tidyverse`, `vegan`, `ggplot2`

## Reproducibility

The code is provided to enable reproduction of the analyses and figures presented in the associated publication.
Where applicable, data are included or referenced within the repository.

## Associated publication

[To Add DOI or link here once published]

## Notes

Some datasets may not be publicly available due to restrictions but can be provided upon request.
