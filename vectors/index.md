---
title       : Vectors
subtitle    : R Language
author      : BRSL
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo		: ../brsl.png
---

## What are Vectors ?

Vector is a set of homegeneous elements. 
ie., elements of same data type

Example:  
1. set of integers  
2. set of numbers ( decimal numbers )  
3. set of charcater values  
4. set of logical values ( boolean values )  
5. set of complex numbers  

---

## How to create a Vector ?

in R language there are various options to create Vectors  
1. using range operator **:**  
2. using combine function c()  
3. using the functions like seq(), rep(), sample(), runif() etc.,

---

## Example Vectors


```r
integers <- -10:10
print(integers)
```

```
##  [1] -10  -9  -8  -7  -6  -5  -4  -3  -2  -1   0   1   2   3   4   5   6
## [18]   7   8   9  10
```


```r
heights <- c(5.1, 5.4, 5.5, 5.6, 5.7, 5.8, 5.9, 6.0)
print(heights)
```

```
## [1] 5.1 5.4 5.5 5.6 5.7 5.8 5.9 6.0
```


--- &radio
## Test your knowledge ( 1/5 )

in R language Vector is a set of

1. images
2. heterogeneous elements
3. _homogeneous elements_
4. files

*** .hint
set of elements of same data type

*** .explanation
the answer is 2



