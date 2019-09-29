# Module 5 - Part to Whole and Ranking Analysis

```{r}

a <- list(
  title = "AXIS TITLE",
  showticklabels = TRUE,
  tickangle = 45,
  exponentformat = "E")
  
library(plotly)
p <- plot_ly(data = df, x = df$Time, y = df$`Average Position`)

p2 <- plot_ly(df, x = df$`Average Position`, y = df$Time, type = 'scatter', mode = 'lines')


#p3 = plot_ly(df, x = df$`Average Position`, y = df$Time, type = ')
p
p2
```

