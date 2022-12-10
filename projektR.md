---
title: "przyczyny stopniowego karłowacenia śledzi oceanicznych wyławianych w Europie"
author: "Radosław Burdziński"
date: "2022-11-15"
output:
  html_document:
    toc: yes
    toc_float: yes
    fig_caption: yes
    number_sections: yes
    keep_md: yes
    word_document: default
---



## Executive summary

Cel analizy to znalezienie przyczyny stopniowego karłowacenia śledzi oceanicznych wyławianych w Europie.

## Wykorzystane biblioteki

```r
library(dplyr)
library(tidyr)
library(ggplot2)
```


```r
   sledzie <- read.csv("sledzie.csv")
   x<-summarise(sledzie)
   x
```

```
## ramka danych z zerową liczbą kolumn oraz 1 wierszem
```

