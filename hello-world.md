Hello World
================
Christopher Kemp
7/12/2020

``` r
# Function Factory
adder <- function(x) {
  function(y) {
    x + y
  }
}

add3 <- adder(3)

add3(5)
```

    ## [1] 8
