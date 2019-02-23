.. R for Data Science documentation master file, created by
   sphinx-quickstart on Thu Feb 21 13:59:58 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to R for Data Science's documentation!
==============================================

Welcome to R for Data Science, a collection of tutorials designed to get students up and running in R even if they have no prior experience with programming. These tutorials are designed to not only provide students with the ability to stitch together code to meet a goal, but also provide students an understanding of the principles of programming in R to help demystify the tool, and improve student confidence in working in R and troubleshooting problems. 

The course is organized as follows:



[**Introduction**](introduction.ipynb)

In this first in a number of tutorials, we’ll cover the very basics of R: how to execute code; how to install and load packages; style; and trouble shooting.

[**Vectors**](vectors.ipynb)

This tutorial introduces a key object in R: vectors. It explains how to create different types of vectors, how to subset them, how to modify them, and how to summarize them.

[**Dataset Basics**](dataset-basics.ipynb)

This tutorial introduces datasets — “data frames” in R. Datasets can be thought of as a collection of vectors stored as columns. We’ll talk about how to create datasets and how to read them from file. We’ll also talk more conceptually about how datasets should be structured.

[**Modifying Data**](modifying-data.ipynb)

Being able to quickly modify datasets — using tasks like subsetting, sorting, extracting unique observations, renaming variables, dropping variables, and creating new variables — is critical. This tutorial explains how to easily do this in R with functions from the dplyr package.

[**Collapsing Data**](collapsing-data.ipynb)

This tutorial explains how to find summary statistics for different categories in a dataset — what is often referred to as collapsing data. Like the tutorial on modifying data, the tutorial draws on a set of intuitive and elegant functions from the dplyr package.

[**Merging & Appending**](merging-appending.ipynb)

This tutorial explains how to combine datasets by merging or appending them. Merging means transferring columns from one dataset to another, while appending means transferring rows from one dataset to another.

[**Wide & Long Data**](wide-and-long.ipynb)

This tutorial explains the difference between long and wide form datasets, shows why it’s generally preferable to use long form datasets, and goes over how to convert datasets from wide to long form.

[**For Loops**](for-loops.ipynb)

This tutorial explains how to write for loops — which can be useful when you want to iterate a process in R — and shows how to use for loops to carry out Monte Carlo simulations.

[**Writing Functions**](writing-functions.ipynb)

This tutorial explains how you can write your own functions in R. After explaining the basics, the tutorial dives into two data science applications for writing functions.

[**Tables in R**](tables-in-r.ipynb)

This tutorial explains how to create and export tables in R. It was originally designed for undergraduate students at Stanford who tend to use Word rather than LaTeX.





.. toctree::
   :maxdepth: 1

   Introduction <introduction>
   Vectors <vectors>
   Datasets <dataset-basics>
   Manipulating Data <modifying-data>
   Collapsing Data <collapsing-data>
   For Loops <for-loops>
   Merging <merging-appending>
   Tables <tables-in-r>
   Reshaping <wide-and-long>
   Functions <writing-functions>

