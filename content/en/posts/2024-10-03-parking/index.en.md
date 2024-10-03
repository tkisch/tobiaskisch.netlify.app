---
title: Parking
author: Tobias Kisch
image: /uploads/posts/parking.png
date: '2024-10-03'
slug: []
categories: []
tags:
  - R
  - Shiny
---

# Shiny Parking App

## Fetch Data from RSS Feed & Leaflet



```r
doct <- read_xml("https://www.pls-zh.ch/plsFeed/rss", encoding="utf-8")
doct <- xmlTreeParse(doct)
```

## Watch Life: [Parking App](https://tobiaskisch.shinyapps.io/leaflet/)