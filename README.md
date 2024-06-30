# LDSF Data Analysis in UK-PACT

## Before we get started...

We will be working in _R Statistics_ for the analysis of LDSF data. The R programming language is a dynamic language built for statistical computing and graphics. R is often used in statistical analysis, scientific computing, machine learning, and data visualization. For a comprehensive introduction to R for data science, [this book is highly recommended](https://r4ds.hadley.nz/). It takes you through the basics of R programming as well as more advanced topics for those already familiar with R. We will not be following the book in the workshop, but it is a great resource for learning R.

## Software needed for this workshop

1. **R Statistics**: You will need to install it on your computer. Navigate to the [R Project website](https://cloud.r-project.org/) and download the latest version of R for your operating system. Follow the installation instructions for your operating system.
2. **VS Code**: This is a versatile code editor that can be used for any programming language. It is lightweight and has a lot of features that make it a great choice for coding. You can download it from the [VS Code website](https://code.visualstudio.com/).
3. Install Quarto from the [Quarto website](https://quarto.org/). Quarto is a document processing tool that allows you to write documents in markdown and R code. We will be using Quarto withon VS Code to write our reports and analyses.

We will cover the below topics at the start of the workshop, so don't worry if you have not completed these steps ahead of the workshop. We will help you get set up. If you feel comfortable installing the software on your own, please go ahead and follow theese steps:

a) Open VS Code and navigate to the Extensions tab on the left sidebar. Search for and install the [R extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=REditorSupport.r).

b) Open R and install the languageserver package by running the following command in the R console:

```R
install.packages("languageserver")
```

_(We will install additional libraries during the workshop as needed.)_

## What will you learn in the workshop?
We will cover a number of topics, including:
- Introduction to R and Quarto
- Quarto notebooks
- Loading LDSF data into R
- Data exploration and visualization
        - Summary statistics
        - Data visualization using ggplot2
        - Mapping data using leaflet
- Statistical analysis of LDSF data using mixed-effects models

All of the above exercises will be hands-on and conducted in Quarto, which is a great tool for reproducible research. Quarto can be used for report writing, data analysis, and creating presentations. It is a versatile tool that can be used for a variety of tasks.
