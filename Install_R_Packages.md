# Install R Packages

## From CRAN

```
a <- available.packages()
class(a)
dim(a)
head(rownames(a), 3)
head(rownames(a), 3)

install.packages("slidify")
## or
install.packages(c("slidify", "ggplot2", "devtool"))

```

## From RStudio

#### Tools -> Install Packages

## From BioConductor

```
source("http://bioconductor.org/biocLite.R")
biocLite()
biocLine(c("GenomicFeatures", "AnnotationDbi"))

```