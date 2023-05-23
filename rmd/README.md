### Build the Book

```
setwd("~/lab/github/BuildingGermaParl/docs")
bookdown::render_book("index.Rmd", "bookdown::gitbook")
bookdown::render_book("index.Rmd", "bookdown::pdf_book")
```
