---
title       :  开源平台OpenStack
subtitle    : 
author      :  张鹏飞
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

--- #montreal bg:url(http://goo.gl/cF6W2)

## Montreal by Night Time

--- #dillinger

<iframe src = 'http://dillinger.io' height='600px'></iframe>

--- .middle 

## Try

---  plot #simple-plot

## A Simple Plot ##

Let us create a simple scatterplot.


```r
require(ggplot2)
```

```
## Warning in library(package, lib.loc = lib.loc, character.only = TRUE,
## logical.return = TRUE, : there is no package called 'ggplot2'
```

```r
qplot(wt, mpg, data = mtcars)
```

```
## Error in eval(expr, envir, enclos): could not find function "qplot"
```

