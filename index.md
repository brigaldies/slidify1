---
title       : My first Slidify'ed slides
subtitle    : Slidify is cool
author      : Bertrand Rigaldies
job         : Data Nerd
framework   : html5slides        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


```r
require(rCharts)
```

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Cars Distance vs. Speed Plot


```r
data(cars)
plot(cars$dist, cars$speed)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

--- .class #id 

## Cars Data


```r
head(cars)
```

```
##   speed dist
## 1     4    2
## 2     4   10
## 3     7    4
## 4     7   22
## 5     8   16
## 6     9   10
```

--- .class #id 

## Cars Speed Histogram


```r
hist(cars$speed)
```

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png)

--- .class #id 

## rChart 1

<iframe src="n1.html" width=100%, height=600></iframe>

--- .class #id
