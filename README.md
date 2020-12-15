
# `tmapr`

[`tmap`](../../../../reymond-group/tmap) is a very fast visualization library
for large, high-dimensional data sets (Probst & Reymond 2020). Currently, `tmap` is available for
`Python` only. `tmap`'s graph layouts are based on the [OGDF](https://ogdf.uos.de/)
library. **The goal of this project is to make the `C++` libraries accessable
through a native `R` interface.**

## Installation

| :exclamation: | Currently not working, please do not install it! |
|---------------|:-------------------------------------------------|

The easiest way to get `tmap` is to install the development version from
GitHub:

```r
# install.packages("devtools")
remotes::install_github("domiden/tmapr")
```

## References

- Probst, D., and Reymond, J.-L. (2020): Visualization of very large high-dimensional data sets as minimum spanning trees. Journal of Cheminformatics 12:12.
  