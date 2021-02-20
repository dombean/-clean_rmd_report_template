Refer to the file __example_html_report.html__ to see what the HTML Report looks like.

The HTML Report is Blue Themed; it comes by default with code folding, code download, numbered sections, floating table of contents, and more.

The HTML Blogdown Template is almost exactly the same as the HTML Report Template. However, an option is added to the YAML for blogdown rendering. Also, there is a fixed table of contents and CSS for scrollable code chunks.

# R Install

1) __Run command in R:__ devtools::install_github("dombean/clean_rmd_report_template")
2) __Quit RStudio__.
3) __Open RStudio__.
3) __Click:__ File --> New File --> R Markdown. The templates should appear under the package name __cleanRMD__.

# Dependencies

install.packages(c("rmarkdown","blogdown"))
