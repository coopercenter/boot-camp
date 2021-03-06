---
output:
  pdf_document: default
  html_document: default
---
# Computing setup 

For the Cooper Center Data Science Boot Camp, please install the software described below on your local machine. 

## R and related resources

We do much of our coding in R, a programming language especially well-suited to statistical computing. For more background, see: [R for Data Science, Section 1.4, "Prerequisites"](https://r4ds.had.co.nz/introduction.html#prerequisites).



### Install R

* [Download and install R](https://cran.rstudio.com/). Follow directions for your machine's operating system.[^3]


[^3]: If you already have R installed on your machine, make sure you're version is later than v. 3.0.1. You can check your current version by running the command `R.Version()` from the R console. The most recent version is: R version 4.0.2 (2020-06-22). 
   

### Install R Studio

[R Studio](https://rstudio.com/products/rstudio/) is an integrated development environment (IDE) for R. It offers a variety of utilities to enhance the experience of coding and generating documents. Unless you already have another IDE you prefer, we suggest you use R Studio. 


* [Download and install R Studio](https://rstudio.com/products/rstudio/download/#download), v. 1.4.1+. 

R Markdown is installed automatically when you install R Studio.[^2] 

[^2]: If you do not install R Studio on your machine, you will need to install and load the `rmarkdown` package for R manually.

### Install the Tidyverse packages for R

The utility of R can dramatically enhanced by the ability to install additional packages that extend its capabilties. The [Tidyverse](https://www.tidyverse.org/) is a collection of packages that extend the capabilities of R for doing data science.

* Install the Tidyverse packages for R: From the Console tab in R Studio (or from R running in a Terminal window), enter:

```r
install.packages("tidyverse")
```
  - Alternatively, you may install these and other packages via the `Packages` tab in R Studio.

### Install LaTeX

In order to generate PDF documents from your R Markdown sessions, you will need to install LaTeX. Several versions (or *distributions*) of LaTeX are available. If you do not already have LaTeX installed on your machine, and don't have any preference between options, then I recommend you install the  [TinyTeX](https://yihui.org/tinytex/) distribution. This is easily done: simply enter the following two lines of code into your R console: 


```r
install.packages('tinytex')
tinytex::install_tinytex()
```



## Git and Github

[Git](https://git-scm.com/) is software for version control. [Github](https://github.com/) is a web service that provides remote storage and access to files via git. By using git and Github together, we greatly facilitate collaboration between multiple individuals working on the same code base, a.k.a. collaborative coding. 

If you have not worked with git and Github before, this short YouTube video provides an orientation to git and Github: [Git and GitHub for an Organized Project (STAT 545 Episode 2-A)](https://www.youtube.com/watch?v=l2ftm-YwJs8) from the University of British Columbia. See also: [Happy Git and GitHub for the useR](https://happygitwithr.com/).


### Install git and link tit to R Studio

[Follow these instructions](https://jennybc.github.io/2014-05-12-ubc/ubc-r/session03_git.html) to [download and install git](https://git-scm.com/downloads) and to link git with R Studio.

**Optional:** Download and install a local [Github desktop client](https://git-scm.com/downloads/guis), or an alternative GUI client.

The git operations you need for this course can be managed within R Studio, from the `Git` tab. Some more advanced operations require using either a Terminal window, or a Git desktop client. 
  
As you get going, you will likely want to learn more about how to work with git and Github. [Review the documentation for git](https://git-scm.com/) and [this Github Guide](https://guides.github.com/introduction/flow/). Learn the basics.


## Other resources

  * [Github organization site](https://github.com/coopercenter), a hub for our work.
  * [Collab site](https://collab.its.virginia.edu), primarily as a shared space to access Zoom for group meetings and recordings..



