Hi there!

* point 1
* point 2

```{r, echo=FALSE}
numericInput("rows", "How many cars?", 5)
renderTable({
  head(cars, input$rows)
})
```

```{r, echo = FALSE}
kmeans_cluster(iris)
```