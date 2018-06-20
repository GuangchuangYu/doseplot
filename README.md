# doseplot

![](https://img.shields.io/badge/lifecycle-dormant-blue.svg)

`doseplot` contains `cnetplot` and `enrichMap` functions for `enrichResult` object. These two functions were re-implemented in `enrichplot` package as `cnetplot` and `emapplot` functions. All other plot functions previous implemented in `DOSE` were moved to `enrichplot`.

This package is just a backup of the old implementation of `cnetplot` and `enrichMap` functions. 

```r
require(DOSE)
data(geneList)
de = names(geneList)[1:100]
x = enrichDO(de)

require(doseplot)
cnetplot(x)
enrichMap(x)
```