# Programming with the Tidyverse

## A Code Clinic tutorial for staff and students at the [Oxford Big Data Institute](https://www.bdi.ox.ac.uk/)

R’s Tidyverse packages make interactive data exploration and modelling fast and fluid (and fun!?). The flip side of this ease of interrogating your data and building models is that using tidyr/dplyr/ggplot code indirectly (i.e. non-interactively within functions or loops) is more challenging. This code clinic will demonstrate the issues that arise when trying to use dplyr/tidyr verbs non-interactively and show you a number of recipes to solve common problems encountered in programming with the Tidyverse.

### Intended Audience

Intermediate users of R who are familiar with the Tidyverse functions but are new to, or struggling with, using these within their own functions and scripts.

### Topics to be covered:

Tidy evaluation (non-standard evaluation)
Data-masking and indirection
Tidy selection
Developing functions based on dplyr/tidyr/ggplot

### Learning Objectives

1. Understand the issues with writing functions that incorporate Tidyverse functions
2. Understand the two forms of non-standard evaluation used in the Tidyverse: Data Masking and Tidy Selection
3. Gain a set of code techniques to solve the problems described above

### Background Knowledge

- Be familiar with R, RStudio
- Be familiar with the Tidyverse – especially have some experience using dplyr, tidyr, and ggplot packages and the %>% syntax
- Understand the basics of writing functions in R and have written at least one function of your own.

### Installation Requirements

1. Install R (versions > 4.0) and RStudio installed ((We recommend using RStudio version 1.4 or later as your IDE to interact with R)
2. Install the following R packages:
   install.packages(c(“tidyverse”, “gapminder”, "palmerpenguins", "testthat"))
