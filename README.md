# MadRaT land data package

R package **mrland**, version **0.49.0.9002**

[![CRAN status](https://www.r-pkg.org/badges/version/mrland)](https://cran.r-project.org/package=mrland) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3822083.svg)](https://doi.org/10.5281/zenodo.3822083) [![R build status](https://github.com/pik-piam/mrland/workflows/check/badge.svg)](https://github.com/pik-piam/mrland/actions) [![codecov](https://codecov.io/gh/pik-piam/mrland/branch/master/graph/badge.svg)](https://app.codecov.io/gh/pik-piam/mrland) [![r-universe](https://pik-piam.r-universe.dev/badges/mrland)](https://pik-piam.r-universe.dev/builds)

## Purpose and Functionality

The package provides land related data via the madrat
    framework.


## Installation

For installation of the most recent package version an additional repository has to be added in R:

```r
options(repos = c(CRAN = "@CRAN@", pik = "https://rse.pik-potsdam.de/r/packages"))
```
The additional repository can be made available permanently by adding the line above to a file called `.Rprofile` stored in the home folder of your system (`Sys.glob("~")` in R returns the home directory).

After that the most recent version of the package can be installed using `install.packages`:

```r 
install.packages("mrland")
```

Package updates can be installed using `update.packages` (make sure that the additional repository has been added before running that command):

```r 
update.packages()
```

## Questions / Problems

In case of questions / problems please contact Jan Philipp Dietrich <dietrich@pik-potsdam.de>.

## Citation

To cite package **mrland** in publications use:

Dietrich J, Mishra A, Weindl I, Bodirsky B, Wang X, Baumstark L, Kreidenweis U, Klein D, Steinmetz N, Chen D, Humpenoeder F, von Jeetze P, Wirth S, Beier F, Hoetten D (2023). _mrland: MadRaT land data package_. doi:10.5281/zenodo.3822083 <https://doi.org/10.5281/zenodo.3822083>, R package version 0.49.0.9002, <https://github.com/pik-piam/mrland>.

A BibTeX entry for LaTeX users is

 ```latex
@Manual{,
  title = {mrland: MadRaT land data package},
  author = {Jan Philipp Dietrich and Abhijeet Mishra and Isabelle Weindl and Benjamin Leon Bodirsky and Xiaoxi Wang and Lavinia Baumstark and Ulrich Kreidenweis and David Klein and Nele Steinmetz and David Chen and Florian Humpenoeder and Patrick {von Jeetze} and Stephen Wirth and Felicitas Beier and David Hoetten},
  year = {2023},
  note = {R package version 0.49.0.9002},
  doi = {10.5281/zenodo.3822083},
  url = {https://github.com/pik-piam/mrland},
}
```
