.. R for Data Science documentation master file, created by
   sphinx-quickstart on Thu Feb 21 13:59:58 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to R for Data Science's documentation!
==============================================

Welcome to R for Data Science, a collection of tutorials designed to get students up and running in R even if they have no prior experience with programming. These tutorials are designed to not only provide students with the ability to stitch together code to meet a goal, but also an understanding of the principles of programming in R to help demystify the tool, and improve student confidence in working in R and troubleshooting problems. 

## Who is this course for?


### Assumed knowledge

This course assumes *zero* programming experience. None. If you can open a web browser, send emails, work in microsoft word, you have enough programming experience for this course. 

### Topics

The goal of this course is to teach a student enough about R to do serious data analysis. However, there are many "flavors" of data science these days, so it's worth emphasizing the type of data science this course is most designed to support. 

This course is designed to serve students who are interested in analyzing data to answer specific questions. For example, it is well suited for social scientists who wish to do statistical analyses of political or economic data, or people advising policymakers on the likely costs of different courses of action. In this kind of data science, analyses of data are usually "one-offs" -- the goal is to analyze a dataset to answer a specific question, not build software that will continuously analyze data on an ongoing basis. 

It is not well suited for people who wish to design programs that, as a part of their operation, analyze data. So if your interest is in writing an iOS app that analyzes user data to make restaurant suggestions, this is probably not the best resource. That kind of data science is closer to "software engineering" (the writing of software programs you plan to distribute to users), for which you will probably find better training in a traditional computer science curriculum.   

## How should I take this course?

Each topic here is presented in two parts: a tutorial that provides instructional materials about the topic in question, and then a set of exercises to allow you to practice the skills you are learning. 

These tutorials will not generally be very long, and we **strongly** recommend that while you read through them you do so with an open programming session so you can just play around a little, trying out the things you learn. 

But the most important thing is for readers to do the exercisesat the end of each tutorial. The research on learning to program is exceedingly clear on this point: **the only way to learn to program is to actually program,** so the more time you spend playing with the tools we are using, making mistakes, and troubleshooting, the more you will learn.

## Why R?

Because it's currently one of the two most-used programs in data science (the other is probably Python), which means that if you want to do data analysis, there is a good chance you'll be called upon to use it, especially when working in teams. Moreover, it's a much easier tool to get started with than a language like Python.

It is worth emphasizing that we're not teaching you R because we think it is necessarily the best tool. The reality is that there are lots of tools for statistical programming, and each has its own strengths and weaknesses (e.g. R, Stata, SPSS, Python, Julia, Matlab, etc.). People develop really strong opinions about what language is *best*, and sometimes pass judgement on people who use other languages. We would like to discourage this type of thinking. Personally, we (Nick and Simon, the authors of this site) regularly work in at least four different programming languages depending on which is best suited to the task at hand, so I think I have reasonable authority to say: there is no single *best* language for all purposes.

As a result, over the course of your career you may find yourself gravitating to one tool or another as required by your research. But in providing you with a firm foundation in a very popular language like R, we feel confident that we will not only be providing you with tools that will allow you to do most everything you'll want to do in graduate school, but we will also be providing you with *generalizable* skills around data manipulation that you will find useful if you later change platforms.

To learn more about the differences between common programming languages, you can find a summary [here](http://www.programmingfords.com/html/languages.html). 

## Who Are We?

This site is based on a set of tutorials originally written by [Simon Ejdmyer](https://sejdemyr.github.io/), and later updated with the help of [Nick Eubank](http://www.nickeubank.com/). We have both been working in "data science" since long before the term became a buzzword in a variety of capacities, including as policy advisors, social scientists, legal experts, and tech company employees. Today, Simon is a Quantitative Researcher at Facebook, and Nick is an Assistant Research Professor in the Social Science Research Institute at Duke University. 


## Course Organization

The course is organized as follows:

:doc:`Introduction <introduction>`

In this first in a number of tutorials, we’ll cover the very basics of R: how to execute code; how to install and load packages; style; and trouble shooting.

:doc:`Vectors <vectors>`

This tutorial introduces a key object in R: vectors. It explains how to create different types of vectors, how to subset them, how to modify them, and how to summarize them.

:doc:`Dataset Basics <dataset-basics>`

This tutorial introduces datasets — “data frames” in R. Datasets can be thought of as a collection of vectors stored as columns. We’ll talk about how to create datasets and how to read them from file. We’ll also talk more conceptually about how datasets should be structured.

:doc:`Modifying Data <modifying-data>`

Being able to quickly modify datasets — using tasks like subsetting, sorting, extracting unique observations, renaming variables, dropping variables, and creating new variables — is critical. This tutorial explains how to easily do this in R with functions from the dplyr package.

:doc:`Collapsing Data <collapsing-data>`

This tutorial explains how to find summary statistics for different categories in a dataset — what is often referred to as collapsing data. Like the tutorial on modifying data, the tutorial draws on a set of intuitive and elegant functions from the dplyr package.

:doc:`Merging & Appending <merging-appending>`

This tutorial explains how to combine datasets by merging or appending them. Merging means transferring columns from one dataset to another, while appending means transferring rows from one dataset to another.

:doc:`Wide & Long Data <wide-and-long>`

This tutorial explains the difference between long and wide form datasets, shows why it’s generally preferable to use long form datasets, and goes over how to convert datasets from wide to long form.

:doc:`For Loops <for-loops>`

This tutorial explains how to write for loops — which can be useful when you want to iterate a process in R — and shows how to use for loops to carry out Monte Carlo simulations.

:doc:`Writing Functions <writing-functions>`

This tutorial explains how you can write your own functions in R. After explaining the basics, the tutorial dives into two data science applications for writing functions.

:doc:`Tables in R <tables-in-r>`

This tutorial explains how to create and export tables in R. It was originally designed for undergraduate students at Stanford who tend to use Word rather than LaTeX.




.. toctree::
   :hidden:
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

