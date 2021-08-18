# EBM

EBM is an R package for maximum likelihood estimation of k-box stochastic energy balance models.

## How to cite

Cummins, D. P., Stephenson, D. B., & Stott, P. A. (2020). Optimal Estimation of Stochastic Energy Balance Model Parameters, *Journal of Climate, 33*(18), 7909-7926, [https://doi.org/10.1175/JCLI-D-19-0589.1](https://doi.org/10.1175/JCLI-D-19-0589.1)

The EBM package is archived on Zenodo and has its own digital object identifier (DOI):

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5217603.svg)](https://doi.org/10.5281/zenodo.5217603)

## Getting started

EBM can be installed directly from GitHub using the [devtools](https://cran.r-project.org/package=devtools) package for R.

### Installing devtools

To install devtools from [CRAN](https://cran.r-project.org/), open an R session and run

```
install.packages("devtools")
```

If devtools requires compilation on your system this step may take a few minutes.

### Installing EBM

To install EBM using devtools, run

```
devtools::install_github("donaldcummins/EBM")
```

Once installed, EBM can be loaded into an R session using

```
library(EBM)
```

## Licence

EBM is licenced under the GNU General Public License v3.0 - see the [LICENCE](LICENCE) file for details.

## Acknowledgements

EBM depends on the following R packages:

* [expm](https://cran.r-project.org/package=expm)
* [FKF](https://cran.r-project.org/package=FKF)
* [nloptr](https://cran.r-project.org/package=nloptr)
* [numDeriv](https://cran.r-project.org/package=numDeriv)

We thank the respective authors for making their software available.





