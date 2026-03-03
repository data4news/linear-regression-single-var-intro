# linear-regression-single-var-intro

Introduction to single-variable linear regression in R using the `mtcars` dataset. Notebooks use `rpy2` to run R inside Jupyter.

## Notebooks

**[mtcars-linear-regression.ipynb](mtcars-linear-regression.ipynb)** — guided walkthrough
- EDA: correlation matrix, faceted scatter plots of all variables vs. `mpg`
- Fit `lm(mpg ~ wt)`, interpret summary output, plot regression line
- Extract predictions and residuals, visualize residuals

**[mtcars-linear-regression-2.ipynb](mtcars-linear-regression-2.ipynb)** — practice exercises
- Repeat the `mpg ~ wt` analysis, then extend to `mpg ~ hp`, `mpg ~ disp`, and `mpg ~ qsec`
- Interpret p-values, R², and residuals for each model

## Setup

Requires Python with `rpy2`, `pandas`, `numpy`, `matplotlib`, and an R installation with `tidyverse` and `corrplot`.
