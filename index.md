---
title       : My first Slidify'ed slides
subtitle    : Slidify is cool
author      : Bertrand Rigaldies
job         : Data Nerd
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


```r
data(cars)
plot(cars$dist, cars$speed)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

--- .class #id 

## Slide 3


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

## Slide 4


```r
hist(cars$speed)
```

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png)
