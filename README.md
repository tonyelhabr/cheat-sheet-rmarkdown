
A [LaTex](https://www.latex-project.org/) template to use with [`{rmarkdown}`](https://rmarkdown.rstudio.com/) to create a compact cheat sheet for school.

To use it, include the following in Rmarkdown YAML header.

````
---
output:
  pdf_document:
    template: {/path/to/template.tex}
---
```