# plessy_oikgenomes_drat
(The name of Analysis of synteny loss and consevation, and of breakpoint sequence motifs, in comparisons between Oikopleura dioica species
[Drat](https://eddelbuettel.github.io/drat/) repository for hosting oik [BSgenome](https://bioconductor.org/packages/BSgenome) packages

## Example installation

```{r}
install.packages("BSgenome.Odioica.local.OSKA2016v1.9", repos="https://oist.github.io/plessy_oikgenomes_drat/")
```

## Example upload

(Assumes that this repository was cloned in `~/Projects/oikgenomes_drat/`)

In `R`:

```{r}
drat::insertPackage(file="~/Projects/Oik_syntenies/BSgenome.Odioica.local.OSKA2016v1.9_1.0.0.tar.gz", repodir = "~/Projects/oikgenomes_drat/docs")
```

Then in the shell console, `git push`.
