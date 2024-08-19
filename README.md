# Quarto templates for [SQL Course](https://iangow.github.io/sql_book/)

## Setting up your computer

Assuming that you have the ability to install software, setting up your computer so that you can run the code in this course is straightforward and takes just a few minutes.
We list the required steps below:

1. Download and install R.
R is available for all major platforms (Windows, Linux, and MacOS) [here](https://cloud.r-project.org).

2. Download and install RStudio. 
An open-source version of RStudio is available [here](https://www.rstudio.com/products/rstudio/download/#download).

3. Install required packages from [CRAN](https://cran.r-project.org).
CRAN stands for "Comprehensive R Archive Network" and is the official repository for **packages** (also known as **libraries**) made available for R.
  In this course, we will make use of a number of R packages.
  These can be installed easily by running the following code in RStudio.^[You can copy and paste the code into the "Console" in RStudio.]


``` r
install.packages(c("tidyverse", "duckdb"))
```

4. Download this repository and save in a location on your computer.

  - Provide instructions here.

5. Open the file `sql_templates.Rproj` in RStudio.

  - Provide instructions here.

## Templates

Each template below shares its name with the corresponding chapter in the [book](https://iangow.github.io/sql_book/).

| Chapter | Template 
|---------|---------------------|
| Time-series analysis | [time-series.qmd](https://raw.githubusercontent.com/iangow/far_templates/main/time-series.qmd) |