
<!-- README.md is generated from README.Rmd. Please edit that file -->

# lems-emt-pdl1-models-figures

<!-- badges: start -->

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8114631.svg)](https://doi.org/10.5281/zenodo.8114631)
<!-- badges: end -->

Models and code to generate figures for “Tumor-Mediated
Immunosuppression and Cytokine Spreading Affects the Relation Between
EMT and PD-L1 Status”. Frontiers in Immunology. doi:
10.3389/fimmu.2023.1219669

## Usage

### Models

COPASI and Morpheus models can be found in `models/copasi_models` and
`models/morpheus_models`, respectively.

### Figures

Figures are generated reproducibly in R using
[`renv`](https://rstudio.github.io/renv/index.html):

1.  Download/clone this repository

2.  Open the project file (`.Rproj`) in RStudio

3.  Run

    ``` r
    renv::restore()
    ```

    to install R package dependencies.

4.  Open `code.Rmd` and choose *Run* \> *Run All*. Figures will appear
    in the `output` folder.

------------------------------------------------------------------------
