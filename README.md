# disdat

## Data for Evaluating Species Distribution Modelling Methods

This package consists of a collection of datasets that can be used to compare species distribution models. There are data for 6 regions in the world, for a total of 226 anonymised species including birds, vascular plants, reptiles and bats. Each data set has presence-only (and optionally background) training data to build models, and presence/absence data to evaluate models.


## Installation

The package is [available from CRAN](https://cran.r-project.org/web/packages/disdat/index.html). You can install it with `install.packages("disdat")`. 

To install the github development version, you can use the `remotes` package like this

```
library(remotes)
remotes::install_github("rspatial/disdat")
```

## Citation

To cite the use of the data and the **disdat** package in publications, please use:

Elith, J., Graham, C.H., Valavi, R., Abegg, M., Bruce, C., Ferrier, S., Ford, A., Guisan, A., Hijmans, R.J., Huettmann, F., Lohmann, L.G., Loiselle, B.A., Moritz, C., Overton, J.McC., Peterson, A.T., Phillips, S., Richardson, K., Williams, S., Wiser, S.K., Wohlgemuth, T. & Zimmermann, N.E., (2020). **Presence-only and presence-absence data for comparing species distribution modeling methods.** Biodiversity Informatics 15: 69-80.
