---
title: "Quarto PowerPoint Example"
format: pptx
editor: visual
---





## Quarto

Quarto enables you to weave together content and executable code into a finished presentation. To learn more about Quarto presentations see <https://quarto.org/docs/presentations/>.

## Bullets

When you click the **Render** button a document will be generated that includes:

-   Content authored with markdown
-   Output from executable code

## Slide with Code and Output


::: {.cell}

```{.r .cell-code}
summary(cars)
```

::: {.cell-output .cell-output-stdout}
```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```
:::
:::


## Slide with Plot


::: {.cell}
::: {.cell-output-display}
![](Quarto_Powerpoint_Example_files/figure-pptx/pressure-1.png)
:::
:::


## Star Wars Plot from Week 1


::: {.cell layout-align="center"}
::: {.cell-output-display}
![](Quarto_Powerpoint_Example_files/figure-pptx/formatted starwars plot-1.png){fig-align='center'}
:::
:::

