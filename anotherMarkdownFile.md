---
title: "First_markdown_file"
author: "alfredofp"
date: "22 1 2022"
output: pdf_document
urlcolor: blue
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```
## This is a new part
```{r}
print("Hello world")
```
## Tests
~~texto~~
see <http://rmarkdown.rstudio.com>.
[text that is shown3](http://rmarkdown.rstudio.com)

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
