---
title: "Exploring the Cars Dataset - html"
layout: post
output:
  html_document:
    keep_md: true
  md_document:
    variant: gfm
    preserve_yaml: true
---



This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

same with kable


```r
kable(summary(cars))
```

         speed           dist      
---  -------------  ---------------
     Min.   : 4.0   Min.   :  2.00 
     1st Qu.:12.0   1st Qu.: 26.00 
     Median :15.0   Median : 36.00 
     Mean   :15.4   Mean   : 42.98 
     3rd Qu.:19.0   3rd Qu.: 56.00 
     Max.   :25.0   Max.   :120.00 



```r
# here is some more code
a <- rnorm(10)
b <- rnorm(10)
model <- lm(a~b)
summary(model)
```

```
## 
## Call:
## lm(formula = a ~ b)
## 
## Residuals:
##      Min       1Q   Median       3Q      Max 
## -1.42569 -0.77075 -0.01574  0.59072  1.65345 
## 
## Coefficients:
##             Estimate Std. Error t value Pr(>|t|)
## (Intercept) 0.368401   0.343879   1.071    0.315
## b           0.005283   0.233340   0.023    0.982
## 
## Residual standard error: 1.08 on 8 degrees of freedom
## Multiple R-squared:  6.408e-05,	Adjusted R-squared:  -0.1249 
## F-statistic: 0.0005127 on 1 and 8 DF,  p-value: 0.9825
```


> Here is now some quote

And this is a list:

- First point
- Second point

And a table:

First | asdf
----- | -----
dd  | ddd
iek  |  dfdf

You can also embed plots, for example:

![]({{ site.baseurl }}/assets/exploring-the-cars-dataset-my-first-plot-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
