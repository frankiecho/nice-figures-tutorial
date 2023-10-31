# Making Figures Look Nice in R (ggplot)

Author: Frankie Cho

This repository contains materials for a tutorial on styling scientific figures in `ggplot`, a popular solution for producing scientific figures in the R programming language. In this tutorial I focus on an example from ecological data, demonstrating how to do so using charts using data from the Queensland government Department of Environment and Science (DES) koala monitoring program (2010-2015), freely accessible on the DES open data portal. All the data can be downloaded freely online with links contained within the main Quarto file, `ggplot-figures.qmd`.

This tutorial will not cover how these charts are made from the downloaded data - for that the participant is referred to study the code in the quarto file and adapt it to their needs. Rather this tutorial will cover how to convert default outputs from R to suit the needs of publication and reduce visual clutter. The end goal is to make the participant aware of the several possible options and external packages available to their disposal to quickly improving the aesthetics of the figures.

An R and RStudio installation is recommended for executing the main Quarto file in full. Afterwards, the dependencies of the Quarto file can be installed as follows:

```         
install.packages(c('geodata', 'ggplot2', 'ggpubr', 'janitor', 'lubridate', 'patchwork', 'see', 'sf', 'tidyverse', 'dplyr', 'rmarkdown'))
```
