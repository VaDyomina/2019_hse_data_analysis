### 1.1

``` r
integrate(function(x){dlnorm(x, mean = 3, sd=0.5)}, 25, 50)
```

    ## 0.2967106 with absolute error < 3.3e-15

### 1.2

``` r
integrate(function(x){dlnorm(x, mean = 3, sd=0.5)}, qlnorm(0.1, mean = 3, sd = 0.5), qlnorm(0.9, mean = 3, sd = 0.5))
```

    ## 0.8 with absolute error < 5.7e-12
