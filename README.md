# AACCUniv2022_reports_dashboards
Materials for the 2022 AACC University course -- Doing More with R: Create Your Own Automated Reports and Dashboards

### Download course files
Please download the course materials from this GitHub repository.
 
1.	Click on the green ‘(download) Code’ button
2.	Select ‘Download ZIP’
3.	Move the file to a location you can easily access (and have read/write permissions for) and unzip its contents

### Install required R packages
In addition to the course materials, we will use several R packages that need to be installed. These are downloaded from the internet and depending on the size and available bandwidth, may take several minutes. To save time, we would like for you to install these packages before the course begins. This way when we need to use the package in our code, it will be available on your system. You should have previously installed the tidyverse package, per the instructions for installing R and RStudio. 

General packages: At the console prompt, or in an R script, type (or copy) and run the following code:

install.packages(c("flexdashboard", "plotly", "lubridate", "kableExtra", "dygraphs", "DT", "xts", "highcharter", "janitor", "here", "readxl", "shiny", "knitr"))

Tinytex: To create PDF documents from R Markdown, you will need to have a LaTeX distribution installed. It is recommended that R Markdown users install TinyTeX as their LaTeX distribution. This install may take 30 min or more. We’ll use the tinytex R package for this install. Type (or copy) the following code into the console prompt or an R script and run:

install.packages('tinytex')
tinytex::install_tinytex()
tinytex::pdflatex('test.tex')
![image](https://user-images.githubusercontent.com/75760807/180209101-b31e7874-1fb1-4bc6-997c-ebaf3e2ca4e5.png)


