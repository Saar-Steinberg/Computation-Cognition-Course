# Computation & Cognition

R Markdown coursework exploring statistical analysis, computational models of cognition, and reinforcement learning.

## Assignments

| Assignment | Topics | Source |
| --- | --- | --- |
| Exercise 3 | R fundamentals, data cleaning, exploratory analysis, and visualization of Breaking Bad episode ratings | [Submission notebook](assignments/EX3/EX3/Ex3.Rmd) |
| Exercise 6 | Stochastic simulation of student progress, cumulative scores, and distributions | [Notebook](assignments/EX6/EX6.Rmd) |
| Homework 1 | Drift Diffusion Model simulations: evidence accumulation, reaction times, and accuracy | [Notebook](assignments/HW1/HW1.Rmd) |
| Homework 2 | Reinforcement learning: learning curves and computational analysis of behavior | [Notebook](assignments/HW2/HW2.Rmd) |

Exercise 3 also includes the original [alternate notebook](assignments/EX3/assignment.Rmd) and [classwork version](assignments/EX3/Tirgul%203%20-%20classwork%20BreakingBad.Rmd). These versions are retained separately. The Homework 1 notebook has an internal title of “Homework 4”; its supplied folder name is retained.

## Working with the code

Open the `.Rmd` notebooks in RStudio to inspect the explanations and run individual R chunks, or knit a complete report.

```r
install.packages(c("rmarkdown", "knitr", "ggplot2", "dplyr", "tidyr", "gridExtra"))
```

Exercise 3 expects `BreakingBadData.csv`, and Homework 2 expects `LearningData.csv`, in their working directories. Datasets are not included in this source-only repository; supply the original course data locally before running those notebooks. RStudio includes Pandoc for HTML rendering. PDF rendering additionally requires LaTeX.

The code has not been rerun for this import. Simulations may produce different results between runs.

## Scope

This repository contains six assignment R Markdown source files and this README. Assignment contents are preserved except for the authorized removal of a personal identifier. Rendered reports, datasets, archives, session files, lecture materials, standalone R scripts, and instructor tutorial notebooks are excluded from the current version.
