Module 5 - Part to Whole and Ranking Analysis
================

``` r
library(readxl)
df <- read_excel("C:/Users/adamw/Downloads/Module # 5.xlsx")
```

``` r
a <- list(
  title = "AXIS TITLE",
  showticklabels = TRUE,
  tickangle = 45,
  exponentformat = "E")
  
library(plotly)
```


``` r
p <- plot_ly(data = df, x = df$Time, y = df$`Average Position`, type = 'scatter', mode = 'lines')

p2 <- plot_ly(df, x = df$`Average Position`, y = df$Time, type = 'scatter', mode = 'lines')


#p3 = plot_ly(df, x = df$`Average Position`, y = df$Time, type = ')
p
```

![](Module-5_files/figure-markdown_github/unnamed-chunk-2-1.png)

``` r
p2
```

![](Module-5_files/figure-markdown_github/unnamed-chunk-2-2.png)
