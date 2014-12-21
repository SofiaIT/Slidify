---
title       : Body Fat Clustering 
subtitle    : Project for the Course in "Developing Data Products"  
author      : Sofia Cividini - BSc, MSc, MSc, MD
job         : Molecular Biologist specialized in Biostatistics and Bioinformatics 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction.

The goal of this application was to create an interactive graph. In fact, through this application, an user can group, in a certain number of clusters, the observations in the data set called bodyfat according to the variables used on the y-axis and on the x-axis of the graph itself.

<img src="assets/fig/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

Source: "Garcia et al. (2005), Improved prediction of body fat by measuring skinfold thickness, circumferences, and bone breadths. Obesity Research, 13(3), 626-634".

---
## Main Characteristics of the data set.

The body fat dataset (bodyfat) is included in the R library called TH.data. It contains body fat measurements and anthropometric measurements which were obtained for 71 healthy German women. The 10 collected variables are the following ones:

Variables     | Explanation
------------- | -------------
DEXfat        | Body fat measured by DXA, response variable
age           | Age in years
waistcirc     | Waist circumference
hipcirc       | Hip circumference
elbowbreadth  | Breadth of the elbow
kneebreadth   | Breadth of the knee.
anthro3a      | Sum of logarithm of three anthropometric measurements.
anthro3b      | Sum of logarithm of three anthropometric measurements.
anthro3c      | Sum of logarithm of three anthropometric measurements.
anthro4       | Sum of logarithm of three anthropometric measurements.


---
## My application.

<img src="C:/Users/Sofia Cividini/Desktop/Application.png" align="left" height="600" width="1000">

---
## Conclusion.

This is a funny application which allows to see how the several observations are grouped in different clusters according to the combined use of 6 variables out of 10 from the original data set. <br/ > For example, it is possible to keep fixed the variable corresponding to the body fat (DEXfat) on the y-axis and see how the observations are put in different clusters according to the values of the waist circumference or to the values of the hip circumference on the x-axis. <br/ >
                                                                                   

<img src="C:/Users/Sofia Cividini/Desktop/bodyfat.jpg" align="right" height="300" width="340">
<br/ >
<br/ >
<br/ >
<p>In the figure, there are the main three different phenotypes <br> of body fat: low, medium and 'high'.</p> 





