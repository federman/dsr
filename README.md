# `>` Introduction to Data Science with R

> [François Briatte](https://f.briatte.org/)  
> Spring ~~2017~~ 2023. __Work in progress.__

`>` __[Syllabus](https://f.briatte.org/teaching/syllabus-dsr.pdf)__

This repo contains files from an old course project that took 5 years to actually get taught. I'm giving it a go this semester, so all old content is gone, and will be replaced, if everything goes well, by some new sessions.

A provisional outline follows. Ideally, we'd also find time for a session to wrap up and to introduce tools that are not covered here. By order of priority: SQL, Git/GitHub, R Markdown, and possibly some JavaScript visualization libraries.

This folder contains the code, data and documentation of the examples used either during the practice sessions in class, or distributed as homework exercises. __Slides are hosted elsewhere, and the links are not currently active.__

# Handbooks

Early in the course, we will rely on R-focused handbooks, all of which are readable online:

- Irizarry, _[Introduction to Data Science](http://rafalab.dfci.harvard.edu/dsbook/)_, 2022
- Rodrigues, _[Modern R with the tidyverse](https://modern-rstats.eu/)_, 2022
- Wickham and Grolemund, _[R for Data Science](https://r4ds.had.co.nz/index.html), 2022 (ongoing updates)
- Healy, _[Data Visualization. A Practical Introduction](https://socviz.co/)_

I will also recommend downloading and using [R cheatsheets](https://github.com/rstudio/cheatsheets).

Later in the course, we will continue with some of those handbooks, but also refer to more reseach-focused ones, which are only available as (paying) PDF books:

- Imai
- Kennedy and Waggoner
- Llaudet and Imai
- Li

… plus a few additional references for good measure.

# Part 1. Basics

## 1. Software

- RStudio interface basics
  - Pane layout
  - Executing code
  - Preferences
- R syntax basics
  - Comments and code
  - Functions, arguments
  - Packages

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-01-software.pdf)__  
`>` Exercise 1: __[Generative art][ex1]__

[ex1]: https://github.com/briatte/dsr/tree/master/dsr-01-exercise

Readings:

- Irizarry, ch. 1, [‘Getting started with R and RStudio’](http://rafalab.dfci.harvard.edu/dsbook/getting-started.html)
- Rodrigues, ch. 1, [‘Getting to know RStudio’](http://modern-rstats.eu/getting-to-know-rstudio.html)
- Wickham and Grolemund, ch. 4 ([‘Workflow: basics’](https://r4ds.had.co.nz/workflow-basics.html))
- Wickham and Grolemund, ch. 6 ([‘Workflow: scripts’](https://r4ds.had.co.nz/workflow-scripts.html))

Video:

- Bail, ["Installing R and RStudio"](https://youtu.be/ulIv0NiVTs4) (also covers RStudio basics)

## 2. Workflow

- Setting the working directory
- Doing so by clicking RStudio project files (`.Rproj`)
- More R syntax essentials:
  - Packages, functions, objects and pipes (`%>%`)
  - Executing code spanning multiple lines
  - Data frames (with rows/observations and columns/variables)
  - R has many packages and sub-syntaxes (base, `tidyverse`, `ggplot2`, etc.)
  - Executing code down to a given line (`Ctrl-Alt-B`)

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-02-workflow.pdf)__  
`>` Class example 1: __[Cholera deaths in London, 1854][s2-1]__  
`>` Class example 2: __[Industrial disputes and left-wing seat shares, 1960s-2010s][s2-2]__  
`>` Exercise 2: __[Weird R syntax][ex2]__

[s2-1]: https://github.com/briatte/dsr/tree/master/dsr-02/01-cholera-1854
[s2-2]: https://github.com/briatte/dsr/tree/master/dsr-02/02-industrial-disputes
[ex2]: https://github.com/briatte/dsr/tree/master/dsr-02-exercise

Readings:

- Irizarry, ch. 2, [‘R basics’](http://rafalab.dfci.harvard.edu/dsbook/r-basics.html)
- Irizarry, ch. 4, [‘The tidyverse’](http://rafalab.dfci.harvard.edu/dsbook/tidyverse.html) (up to Section 4.8)
- Irizarry, ch. 5 ([‘Importing data’](http://rafalab.dfci.harvard.edu/dsbook/importing-data.html))
<!-- - Llaudet and Imai, ch. 1 (‘Introduction’) -->
- Rodrigues, ch. 2 ([‘Objects, ...’](http://modern-rstats.eu/objects-their-classes-and-types-and-useful-r-functions-to-get-you-started.html))
- Rodrigues, ch. 3 ([‘Reading and writing data’](http://modern-rstats.eu/reading-and-writing-data.html))

Video:

- Bail, ["R basics"](https://youtu.be/vVcH_OvrLEM)

Cheatsheets:

- [Base R](https://github.com/rstudio/cheatsheets/raw/main/base-r.pdf)
- [RStudio IDE](https://github.com/rstudio/cheatsheets/raw/main/rstudio-ide.pdf)
- [R syntax(es)](https://github.com/rstudio/cheatsheets/raw/main/syntax.pdf)
- [Stata to R](https://github.com/rstudio/cheatsheets/raw/main/stata2r.pdf) (if relevant)

## 3. Data

Data wrangling, mostly with `dplyr`.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-03-data.pdf)__  
`>` Class example 1: __[...][s3-1]__  
`>` Class example 2: __[...][s3-2]__  
`>` Exercise 3: __[...][ex3]__

[s3-1]: /
[s3-2]: /
[ex3]: /

## 4. Visualization

Plots, mostly with `ggplot2`.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-04-visualization.pdf)__  
`>` Class example 1: __[...][s4-1]__  
`>` Class example 2: __[...][s4-2]__  
`>` Exercise 4: __[...][ex4]__

[s4-1]: /
[s4-2]: /
[ex4]: /

# Part 2. Essentials

## 5. Description

Also covering sampling, and possibly bootstrapping if time permits.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-05-description.pdf)__  
`>` Class example 1: __[...][s5-1]__  
`>` Class example 2: __[...][s5-2]__  
`>` Exercise 5: __[...][ex5]__

[s5-1]: /
[s5-2]: /
[ex5]: /

## 6. Association

Also covering surveys, and (if time permits) how to handle survey weights.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-06-association.pdf)__  
`>` Class example 1: __[...][s6-1]__  
`>` Class example 2: __[...][s6-2]__  
`>` Exercise 6: __[...][ex6]__

[s6-1]: /
[s6-2]: /
[ex6]: /

## 7. Correlation

Also introducing least squares, and possibly LO(W)ESS.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-07-correlation.pdf)__  
`>` Class example 1: __[...][s7-1]__  
`>` Class example 2: __[...][s7-2]__  
`>` Exercise 7: __[...][ex7]__

[s7-1]: /
[s7-2]: /
[ex7]: /

## 8. Regression

Linear regression, the full package: dummies, interactions, diagnostics, marginal effects. All in one session, if things go well.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-08-regression.pdf)__  
`>` Class example 1: __[...][s8-1]__  
`>` Class example 2: __[...][s8-2]__  
`>` Exercise 8: __[...][ex8]__

[s8-1]: /
[s8-2]: /
[ex8]: /

## 9. Nonlinearity

Focusing mostly on logistic regression, but hoping to also introduce splines and more fun stuff.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-09-nonlinearity.pdf)__  
`>` Class example 1: __[...][s9-1]__  
`>` Class example 2: __[...][s9-2]__  
`>` Exercise 9: __[...][ex9]__

[s9-1]: /
[s9-2]: /
[ex9]: /

## 10. Classification

Dimensionality reduction, clustering, etc.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-10-classification.pdf)__  
`>` Class example 1: __[...][s10-1]__  
`>` Class example 2: __[...][s10-2]__  
`>` Exercise 10: __[...][ex10]__

[s10-1]: /
[s10-2]: /
[ex10]: /

# Part 3. Extras

## 11. Text

Students manifested an interest in that.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-11-text.pdf)__  
`>` Class example 1: __[...][s11-1]__  
`>` Class example 2: __[...][s11-2]__  
`>` Exercise 11: __[...][ex11]__

[s11-1]: /
[s11-2]: /
[ex11]: /

## 12. Maps

Students manifested an interest in that.

`>` __[Slides](https://f.briatte.org/teaching/slides-dsr-12-maps.pdf)__  
`>` Class example 1: __[...][s12-1]__  
`>` Class example 2: __[...][s12-2]__  
`>` Exercise 12: __[...][ex12]__

[s12-1]: /
[s12-2]: /
[ex12]: /

* * *

# Credits

The last time I had a chance to build such a course was [10 years ago, with Ivaylo Petev](https://f.briatte.org/teaching/ida/). Some of the inspiration for this course dates back to that time.

## Inspiration

- Chris Adolph, [Visualizing Data and Models](https://faculty.washington.edu/cadolph/index.php?page=22) (University of Washington, 2023)
- Grant McDermott, [Data Science for Economists](https://github.com/uo-ec607/) (University of Oregon, 2021)
- Cosma Shalizi, [Undergraduate Advanced Data Analysis](https://www.stat.cmu.edu/~cshalizi/uADA/19/) (Carnegie Mellon University, 2019)
- Cosma Shalizi, [Statistical Computing](https://www.stat.cmu.edu/~cshalizi/statcomp/14/) (Carnegie Mellon University, 2014)
- Cosma Shalizi, [Modern Regression](https://www.stat.cmu.edu/~cshalizi/mreg/15/) (Carnegie Mellon University, 2015)
