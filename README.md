
## `DiallelAnalysisR`: Diallel Analysis with R

    Error in get(genname, envir = envir) : object 'testthat_print' not found

###### Version : [0.4.0](https://myaseen208.github.io/DiallelAnalysisR/); Copyright (C) 2019-2020: [UAF](http://uaf.edu.pk//); License: [GPL-2\|GPL-3](https://www.r-project.org/Licenses/)

##### *Muhammad Yaseen<sup>1</sup>, and Kent M. Eskridge<sup>2</sup>*

1.  Department of Mathematics and Statistics, University of Agriculture
    Faisalabad, Pakistan.
2.  Department of Statistics, University of Nebraska Lincoln, NE, USA.

------------------------------------------------------------------------

[![minimal R
version](https://img.shields.io/badge/R%3E%3D-3.5.0-6666ff.svg)](https://cran.r-project.org/)
[![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version-last-release/DiallelAnalysisR)](https://cran.r-project.org/package=DiallelAnalysisR)
[![rstudio mirror
downloads](https://cranlogs.r-pkg.org/badges/grand-total/DiallelAnalysisR?color=green)](https://CRAN.R-project.org/package=DiallelAnalysisR)
<!-- [![packageversion](https://img.shields.io/badge/Package%20version-0.2.3.3-orange.svg)](https://github.com/myaseen208/DiallelAnalysisR) -->

[![develVersion](https://img.shields.io/badge/devel%20version-0.4.0-orange.svg)](https://github.com/myaseen208/DiallelAnalysisR)

<!-- [![GitHub Download Count](https://github-basic-badges.herokuapp.com/downloads/myaseen208/DiallelAnalysisR/total.svg)] -->

[![Project Status:
WIP](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![lifecycle](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html)
[![Last-changedate](https://img.shields.io/badge/last%20change-2021--02--24-yellowgreen.svg)](https://github.com/myaseen208/DiallelAnalysisR)
[![Rdoc](https://www.rdocumentation.org/badges/version/DiallelAnalysisR)](https://www.rdocumentation.org/packages/DiallelAnalysisR)

------------------------------------------------------------------------

## Description

Performs Diallel Analysis with R using Griffing’s and Hayman’s
approaches. Four different Methods (1: Method-I (Parents + F1’s +
reciprocals); 2: Method-II (Parents and one set of F1’s); 3: Method-III
(One set of F1’s and reciprocals); 4: Method-IV (One set of F1’s only))
and two Models (1: Fixed Effects Model; 2: Random Effects Model) can be
applied using Griffing’s approach.

## Installation

The package can be installed from CRAN as follows:

``` r
install.packages("DiallelAnalysisR", dependencies = TRUE)
```

The development version can be installed from github as follows:

``` r
if (!require("remotes")) install.packages("remotes")
remotes::install_github("myaseen208/DiallelAnalysisR")
```

## What’s new

To know whats new in this version type:

``` r
news(package = "DiallelAnalysisR")
```

## Links

[CRAN page](https://cran.r-project.org/package=DiallelAnalysisR)

[Github page](https://github.com/myaseen208/DiallelAnalysisR)

[Documentation website](https://myaseen208.github.io/DiallelAnalysisR/)

## Citing `DiallelAnalysisR`

To cite the methods in the package use:

``` r
citation("DiallelAnalysisR")
```


    To cite the R package 'DiallelAnalysisR' in publications use:

      Muhammad Yaseen, and Kent M. Eskridge (2021).  DiallelAnalysisR:
      Diallel Analysis with R.R package version 0.4.0 ,
      https://myaseen208.github.io/DiallelAnalysisR/https://cran.r-project.org/package=DiallelAnalysisR.

    A BibTeX entry for LaTeX users is

      @Manual{,
        title = {DiallelAnalysisR: Diallel Analysis with R},
        author = {{Muhammad Yaseen} and {Kent M. Eskridge} and {Pedro A. M. Barbosa}},
        year = {2021},
        note = {R package version 0.4.0},
        note = {https://myaseen208.github.io/DiallelAnalysisR/ },
        note = {https://cran.r-project.org/package=DiallelAnalysisR},
      }

    This free and open-source software implements academic research by the
    authors and co-workers. If you use it, please support the project by
    citing the package.
