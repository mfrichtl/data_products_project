---
title       : Developing Data Products Course Project
subtitle    : 
author      : Matt Frichtl
job         : 
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
revealjs    : {theme: solarized, transition: cube}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

# Developing Data Products
## Course Project

### Matt Frichtl

---

## Trigonometric Graphing Application
### Developing Data Products Course Project

- An interactive application for graphing sine and cosine functions.


```r
x <- seq(0, 25, 0.01)
plot(x, sin(x), type = "p", xlab = "x", ylab = "Response")
```

<img src="assets/fig/graph_slide_2-1.png" title="plot of chunk graph_slide_2" alt="plot of chunk graph_slide_2" style="display: block; margin: auto;" />

--- .class #slide 

### Never forget what sine & cosine functions look like again!


```r
x <- seq(0, 25, 0.01)
plot(c(x, x), c(sin(x), cos(x)), type = "p", xlab = "x", ylab = "Response")
```

<img src="assets/fig/graph_slide_3-1.png" title="plot of chunk graph_slide_3" alt="plot of chunk graph_slide_3" style="display: block; margin: auto;" />

--- .class #slide -

### Or what changes to the function parameters do!


```r
x <- seq(0, 25, 0.01)
plot(c(x, x), c(4 * sin(x), cos(4 * x)), type = "p", xlab = "x", ylab = "Response")
```

<img src="assets/fig/graph_slide_4-1.png" title="plot of chunk graph_slide_4" alt="plot of chunk graph_slide_4" style="display: block; margin: auto;" />

--- .class #slide -

### Easy to modify --- add other parameters as well


```r
x <- seq(0, 25, 0.01)
plot(c(x, x), c(x * sin(x), cos(x^2)), type = "p", xlab = "x", ylab = "Response")
```

<img src="assets/fig/graph_slide_5-1.png" title="plot of chunk graph_slide_5" alt="plot of chunk graph_slide_5" style="display: block; margin: auto;" />
