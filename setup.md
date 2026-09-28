# Course Setup

## Software

The course uses **R** as its primary analytical environment and **Quarto** for course materials and practical exercises.

Participants should have the following installed before the course:

* R

* RStudio or another suitable R environment

* Quarto

Recent versions are recommended.

## R packages

The course uses a relatively small collection of established R packages. These can be installed with:

```
install.packages(c(
  "ggplot2",
  "mgcv",
  "lme4",
  "glmmTMB",
  "MASS"
))
```

Additional packages may be introduced where they provide a clear analytical purpose.

The emphasis throughout the course is on transparent, readable code rather than learning a large software ecosystem.

## Check your installation

Start R and confirm that packages can be loaded normally:

```
library(ggplot2)
library(mgcv)
library(lme4)
library(glmmTMB)
library(MASS)
```

To check that Quarto is available, open a terminal and run:

```
quarto --version
```

## Course materials

Practical exercises use Quarto documents combining explanatory text, R code, figures and statistical output.

Participants will receive the datasets and practical materials required for course delivery.

Detailed installation guidance will be provided before the course where required.
