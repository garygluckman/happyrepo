R Markdown Rocks
================
Gary Gluckman
February 16, 2017

R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

``` r
x <- rnorm(1000)
head(x)
```

    ## [1] -0.9009132 -0.9891018  0.8123826 -0.4574154 -0.2593997 -0.4908902

Including Plots
---------------

You can also embed plots, for example:

![](rmarkdownrocks_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
