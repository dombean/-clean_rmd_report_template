Refer to the file __example_html_report.html__ to see what the HTML Report looks like.
Refer to the file __example_html_presentation.html__ to see what the HTML Presentation looks like.

The __HTML Report__ is Blue Themed; it comes by default with code folding, code download, numbered sections, floating table of contents, and more.

The __HTML Blogdown__ Template is almost exactly the same as the __HTML Report__ Template. However, an option is added to the YAML for blogdown rendering. Also, there is a fixed table of contents and CSS for scrollable code chunks.

The __HTML Presentation__ is Blue Themed; it comes with a [macro for easy image scaling](https://bookdown.org/yihui/rmarkdown/some-tips.html#macros).

# R Install

1) __Run command in R:__ devtools::install_github("dombean/clean_rmd_report_template")
2) __Quit RStudio__.
3) __Open RStudio__.
3) __Click:__ File --> New File --> R Markdown --> From Template. The templates should appear under the package name __cleanRMD__.

# Dependencies

install.packages(c("rmarkdown","blogdown","xaringan"))
