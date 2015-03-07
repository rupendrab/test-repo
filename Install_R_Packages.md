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

# Check if a package is already installed
find.package("devtool")
find.package("ggplot2")

```

## From RStudio

#### Tools -> Install Packages

## From BioConductor

```
source("http://bioconductor.org/biocLite.R")
biocLite()
biocLine(c("GenomicFeatures", "AnnotationDbi"))

```

http://bioconductor.org/install

## Load packages

```
library(ggplot2)
# All dependencies are loaded first
# Do not put the package name in quotes
search()
```