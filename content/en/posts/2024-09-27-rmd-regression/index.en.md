---
title: rmd Regression
author: Tobias Kisch
date: '2024-09-27'
slug: []
categories: []
tags: []
---

We build a linear regression below.


```r
fit = lm(dist ~ speed, data = cars)
b = coef(summary(fit))
plot(fit)
```

<img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-1-1.png" width="672" /><img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-1-2.png" width="672" /><img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-1-3.png" width="672" /><img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-1-4.png" width="672" />

The slope of the regression is 3.9324088.
