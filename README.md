# Example

```{r dsamp}
library('geom_taco')
ggplot(iris) + aes(meat = Species, salsa = Sepal.Length) + geom_taco()
```
  
# Install 

```r
library("devtools")
install_github("geom_taco", "tlevine")
```

Windows users also must first install
[Rtools](http://cran.rstudio.com/bin/windows/Rtools/).
