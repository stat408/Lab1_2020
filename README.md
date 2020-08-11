Lab 1
================
Group Member Names - here

## Lab Overview

One interesting characteristic of Severe Acute Respiratory Syndrome
coronavirus 2 (SARS-CoV-2), the virus that causes COVID-19, is the
prevalence of asymptomatic cases and the ability of asymptomatic
carriers to infect others. While there are many public health
implications of asymptomatic spread, this question will explore clinical
and immunological measurements of symptomatic and asymptomatic patients.
Specifically of interest will be antibodies which are proteins in the
blood that develop to neutralize, in this case, the SARS-CoV-2 virus.
Furthermore, the presence of antibodies is commonly linked with immunity
to future infections.

An recent article published in Nature Medicine titled *Clinical and
immunological assessment of asymptomatic SARS-CoV-2 infections* contains
a comparative study of symptomatic and asymptomatic patients. The paper
freely available at the **[following
link](https://www.nature.com/articles/s41591-020-0965-6)**.

## Questions

Answer the following questions in this R Markdown document. Please
include code where necessary.

Download some of the data from the article, which is available at:

``` r
library(tidyverse)
Covid_data <- read_csv("http://math.montana.edu/ahoegh/Data/Covid_3a.csv")
```

#### 1\.

Describe the variables in the dataset.

#### 2\.

Use the `group_by()` function along with `summarize()` to calculate the
mean `IgG S/CO` value for the two groups (symptomatic and asymptomatic)
in the dataset.

#### 3\.

Using `ggplot2` create a figure that compares the `IgG S/CO` value for
the symptomatic and asymptomatic groups.
