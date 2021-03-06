---
title: "Design and Analysis Tools"
hero_image: "hero.jpg"
nometadata: true
notags: true
noshare: true
nocomments: true
---

## Web Applications

Several web applications have been developed so that trial designers
can quickly create preference trials based on the desired power, sample size,
and effect size. Each of these applications allow the designer to input 
trial specifications and return visualizations, a table of the trial
design parameters, and R code to reproduce the design.

- Continuous Outcomes
    - [Power](https://kaneplusplus.shinyapps.io/power-determination/)
    - [Sample Size](https://kaneplusplus.shinyapps.io/sample-size/)
    - [Effect Size Calculator](https://kaneplusplus.shinyapps.io/effect-size/)

- Binomial Outcomes
    - [Power](https://kaneplusplus.shinyapps.io/binomial-power/)
    - [Sample Size](https://kaneplusplus.shinyapps.io/binomial-sample-size/)

- Count Outcomes
    - [Power](https://kaneplusplus.shinyapps.io/poisson-power/)
    - [Sample Size](https://kaneplusplus.shinyapps.io/poisson-sample-size/)


## R-Package

For more sophisticated designs and for trial designers who are familiar with
the R programming environment, there is an R package that can be install
via the following command:

```{r}
install.packages("preference")
```

The package code can be found on 
[GitHub](https://github.com/kaneplusplus/preference). Any problems, bugs, or
suggestions for enhancements can be conveyed through the 
[issue tracker](https://github.com/kaneplusplus/preference/issues).
