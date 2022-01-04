# Computing Set Up :computer:

## Install R/RStudio and Configure Git

You can install R/RStudio on your local machine and configure it to work with Git and GitHub. The text [Happy Git and GitHub for the useR](https://happygitwithr.com/) is a great resource to help you install RStudio and configure Git. The steps are outlined below. Click on each link for more detail.

:one: [Install R and RStudio](https://happygitwithr.com/install-r-rstudio.html)
(Note: I recommend installing the desktop version not the preview release)

:two: [Install Git](https://happygitwithr.com/install-git.html)

:three: [Introduce Yourself to Git](https://happygitwithr.com/hello-git.html)

:four: [Configure GitHub authentication](https://github.com/DukeStatSci/github_auth_guide)

## Starter packages

Below is a set of R packages we will use throughout the semester. This list is just to get you started; we will let you know as new R packages are required.

```
install.packages("tidyverse")
install.packages("rmarkdown")
install.packages("broom")
install.packages("knitr")
install.packages("lme4")
```

The [**TinyTex**](https://yihui.org/tinytex/) R package allows you to knit R Markdown documents to PDF. Install TinyTex by running the following code:

```r
install.packages('tinytex')
tinytex::install_tinytex()
```
---

## RStudio Docker Containers

As a Duke student, you have access to RStudio through a [Docker container](https://vm-manage.oit.duke.edu/containers) managed by Duke OIT. These containers are a good resource if you are unable to install RStudio on your local machine or if you have any issues with your local RStudio during the semester. 

Use your NetID to reserve a **generic RStudio** container. It is already set up to utilize version control using Git. [Click here](https://github.com/DukeStatSci/github_auth_guide) for instructions on configuring GitHub authentication. 

