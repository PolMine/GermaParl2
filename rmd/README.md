### Build the Book

```
setwd("~/lab/github/GermaParl2/rmd")
bookdown::render_book("index.Rmd", "bookdown::gitbook")
bookdown::render_book("index.Rmd", "bookdown::pdf_book")
```

### News

#### v2.0.1 [2023-12-22]

* updated documentation for v2.0.1
* temporarily removed pdf version due to an issue with `kableExtra` (probably related to issue 750 of kableExtra)
