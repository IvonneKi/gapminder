Lab3-Gapminder.Rmd
================
Ivonne Kienast
2/26/2021

## Data

ggplot to visually explore global trends in public health and economics
compiled by the Gapminder project. This project was pioneered by Hans
Rosling, who is famous for describing the prosperity of nations over
time through famines, wars and other historic events.

``` r
# install.packages("dslabs")
library(dslabs)
library(tidyverse)
```

    ## -- Attaching packages --------------------------------------- tidyverse 1.3.0 --

    ## v ggplot2 3.3.3     v purrr   0.3.4
    ## v tibble  3.0.6     v dplyr   1.0.3
    ## v tidyr   1.1.2     v stringr 1.4.0
    ## v readr   1.4.0     v forcats 0.5.1

    ## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
?gapminder
```

    ## starting httpd help server ...

    ##  done

``` r
gap2011<- gapminder %>%
  as_tibble() %>%
  filter(year == 2011)
```

## Life expectancy

## Fertility

## Infant Mortality
