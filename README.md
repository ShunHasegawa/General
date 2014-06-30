# How to work with repositories on my account

This project describes how to work with the repositories on my account.

## Clone repository
Firstly you need to clone a repository you'd like to work on to your local directory.

## Restore packages
Once you finished cloning, then restore packages whose versions are stored in packrat folder. Firstly install `packrat`.

```r
if (!require("devtools")) install.packages("devtools")
devtools::install_github("rstudio/packrat", ref = "feature/source-repos")
```