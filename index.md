---
title       : Calculator
subtitle    : Slidify Demo
author      : Tarun Reddy Aleti
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1. Aim of the Project is do show a demo of calculator using R Shiny




2. In ui.R we give inputs and in server.R we use these inputs to estimate the outputs


---
## Examples

1. Addition:
    
    ```r
    a = 1
    b = 2
    c = a + b
    print (c)
    ```
    
    ```
    ## [1] 3
    ```
    
2. Subtraction

    
    ```r
    a = 1
    b = 2
    c = a - b
    print (c)
    ```
    
    ```
    ## [1] -1
    ```

---

3. Multiplication

    
    ```r
    a = 1
    b = 2
    c = a * b
    print (c)
    ```
    
    ```
    ## [1] 2
    ```

4. Division
    
    ```r
    a = 1
    b = 2
    c = a / b
    print (c)
    ```
    
    ```
    ## [1] 0.5
    ```
    <ul> Note
    <li> b cannot be zero </ul>

---

## Summary

1. Successfully demonstrated the Shiny, Shiny App and Slidify applications


2. Demonstrated expected outputs using examples




