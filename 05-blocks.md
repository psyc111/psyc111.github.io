# Blocks

## Equations

Here is an equation.

\begin{equation} 
  f\left(k\right) = \binom{n}{k} p^k\left(1-p\right)^{n-k}
  (\#eq:binom)
\end{equation} 

You may refer to using `\@ref(eq:binom)`, like see Equation \@ref(eq:binom).


## Theorems and proofs

Labeled theorems can be referenced in text using `\@ref(thm:tri)`, for example, check out this smart theorem \@ref(thm:tri).

::: {.theorem #tri}
For a right triangle, if $c$ denotes the *length* of the hypotenuse
and $a$ and $b$ denote the lengths of the **other** two sides, we have
$$a^2 + b^2 = c^2$$
:::

Read more here <https://bookdown.org/yihui/bookdown/markdown-extensions-by-bookdown.html>.

## Callout blocks


The `bs4_book` theme also includes special callout blocks, like this `.rmdnote`.

::: {.rmdnote}
You can use **markdown** inside a block.


```r
#head(beaver1, n = 5)
head(Lock5withR::StudentSurvey, n = 5)
#>        Year Gender Smoke   Award HigherSAT Exercise TV
#> 1    Senior      M    No Olympic      Math       10  1
#> 2 Sophomore      F   Yes Academy      Math        4  7
#> 3 FirstYear      M    No   Nobel      Math       14  5
#> 4    Junior      M    No   Nobel      Math        3  1
#> 5 Sophomore      F    No   Nobel    Verbal        3  3
#>   Height Weight Siblings BirthOrder VerbalSAT MathSAT  SAT
#> 1     71    180        4          4       540     670 1210
#> 2     66    120        2          2       520     630 1150
#> 3     72    208        2          1       550     560 1110
#> 4     63    110        1          1       490     630 1120
#> 5     65    150        1          1       720     450 1170
#>    GPA Pulse Piercings    Sex
#> 1 3.13    54         0   Male
#> 2 2.50    66         3 Female
#> 3 2.55   130         0   Male
#> 4 3.10    78         0   Male
#> 5 2.70    40         6 Female
```

:::

It is up to the user to define the appearance of these blocks for LaTeX output. 

You may also use: `.rmdcaution`, `.rmdimportant`, `.rmdtip`, or `.rmdwarning` as the block name.


The R Markdown Cookbook provides more help on how to use custom blocks to design your own callouts: https://bookdown.org/yihui/rmarkdown-cookbook/custom-blocks.html
