---
title       : Slidify Test
subtitle    : Yay test!
author      : Gareth
job         : cheeseburger
framework   : html5slides # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## R Example

```r
# quick summary and plot
library(ggplot2)
## summary(cars)
qplot(speed, dist, data = cars) + geom_smooth()
```

![plot of chunk qplot](assets/fig/qplot.png) 






