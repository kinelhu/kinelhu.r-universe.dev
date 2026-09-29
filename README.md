# kinelhu.r-universe.dev

The registry for <https://kinelhu.r-universe.dev>, which builds binaries of the packages listed in `packages.json`.

Install from it with no compiler:

```r
install.packages("gghalftone", repos = c("https://kinelhu.r-universe.dev", "https://cloud.r-project.org"))
```

To add a package, append an entry with its `package` name, the public git `url`, and `subdir` if it is not at the repository root. R-universe rebuilds on each push here and on each push to a listed repository.
