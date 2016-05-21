---
title       : Visualizing BMI (Body Mass Index)
subtitle    : 
author      : Eu Wern Teh
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Body Mass Index

BMI (Body Mass Index) is a method to measure your weight category. There are four weight categories in BMI, and they are underweight, normal weight, overweight, or obese. We can identify our health status by looking at which category we belonged to. Ideally, we want to stay in "normal weight" zone because the risk of getting health disease (eg: stroke, diabetes) increases in the other zone. 

--- .class #id 

## BMI Calculation

To calculate BMI, we need our height and our weight. 

```r
height = 1.73 # meter
weight = 73   # KG

BMI = weight/(height^2)
BMI #your BMI
```

```
## [1] 24.39106
```

--- .class #id 

## Visualizing BMI

There are a lot of online BMI calculator but to my knowledge, there is still no application that tries to visualize BMI interactively. This project is an attempt to visualize BMI. 

--- .class #id 

## Visualzing BMI 

In this project, I have created an app that allows user to visualize BMI interactively. 

<img width=900px height=400px src="http://euwern.github.io/dataproduct_slides/demo.png"></img>

--- .class #id 

## Visualizing BMI

As user interactively slides the weight control, the BMI number will change and dependening on which zones it falls into, the color of the bar will change. 

| Weight Category   |      Color      |
|-------------------|:---------------:|
| Underweight       |  red            |
| Normal            |  green          |
| Overweight        |  yellow         |
| Obese             |  red            |








