# Installing RStudio :computer:

You can install RStudio on your local machine and configure it to work with Git and GitHub. The text [Happy Git and GitHub for the useR](https://happygitwithr.com/) is a great resource to help you install RStudio and configure Git. The steps are outlined below. Click on each link for more detail.

:one: [Install or Upgrade R and RStudio](https://happygitwithr.com/install-r-rstudio.html)

:two: [Install Git](https://happygitwithr.com/install-git.html)

:three: [Introduce Yourself to Git](https://happygitwithr.com/hello-git.html)

:four: [Configure GitHub authentication](https://github.com/DukeStatSci/github_auth_guide)

----


:five: You will need to be able to knit to PDF [**TinyTex**](https://yihui.org/tinytex/) R package by running the following code in the console: 

```r
install.packages('tinytex')
tinytex::install_tinytex()
```

:one: **RStudio Docker Container**: As a Duke student, you have access to RStudio through a [Docker container](https://vm-manage.oit.duke.edu/containers) managed by Duke OIT. Use your NetID to reserve a generic **RStudio** container. It is already set up to utilize version control using Git. [Click here](https://github.com/DukeStatSci/github_auth_guide) for instructions on configuring GitHub authentication. 
