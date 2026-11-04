# Computation & Cognition

R and R Markdown assignments exploring statistical analysis, computational models of cognition, and reinforcement learning. Reports include English and Hebrew content.

## Assignment guide

| Material | Focus | Source / report |
| --- | --- | --- |
| Exercise 1 | Introductory R exercise | [R script](coursework/Ex1.R) |
| Exercise 3 | Data cleaning, exploratory analysis, and visualization of Breaking Bad episode data | [R Markdown and dataset](coursework/EX3/EX3) |
| Exercise 6 | Stochastic simulation of student progress and score distributions | [R Markdown](coursework/EX6/EX6.Rmd) · [PDF](coursework/EX6/EX6.pdf) |
| Homework 1 | Drift Diffusion Model: simulated evidence accumulation, response times, and accuracy | [R Markdown](coursework/HW1/HW1.Rmd) · [PDF](coursework/HW1/HW1.pdf) |
| Homework 2 | Reinforcement learning and analysis of learning behavior | [R Markdown](coursework/HW2/HW2.Rmd) · [PDF](coursework/HW2/HW2.pdf) |
| Homework 7 | Submitted written coursework | [PDF](coursework/HW7.pdf) |
| Perceptron | Submitted written coursework | [PDF](coursework/Perceptron.pdf) |

The Homework 1 source is titled “Homework 4” internally; the original folder naming is retained.

## Supporting materials

All supplied course materials are under [`coursework/`](coursework/), preserving their relative folder structure. This includes experiment datasets, rendered HTML reports, original submission ZIPs, lecture and exam preparation materials, and tutorials on reinforcement-learning parameter estimation and model comparison. Tutorial and lecture materials retain their original authorship; they are included as course context, not presented as original student work.

## Running the R notebooks

Use R with RStudio and install the packages required by the notebooks:

```r
install.packages(c("rmarkdown", "knitr", "ggplot2", "dplyr", "tidyr", "tidyverse"))
```

Open an `.Rmd` file and knit it, or run its chunks interactively. Set the working directory to the notebook's folder so relative CSV paths resolve. For Exercise 3, the nested `EX3/EX3` directory contains both the notebook and `BreakingBadData.csv`. Each RL folder contains its own `LearningData.csv`; these datasets should remain alongside their respective notebooks.

HTML rendering requires Pandoc (bundled with RStudio); PDF rendering additionally requires a LaTeX installation. Existing PDFs can be viewed directly on GitHub. Download HTML reports to view them in a browser.

The notebooks were inspected but have not been rerun for this upload. Some simulations use random sampling, so regenerated outputs may differ.

## Preservation

Original coursework content is retained except for removal of a personal identifier from filenames and file contents, including PDF reports and nested archives. Existing duplicate versions and submission archives are preserved. This README is new repository documentation.
