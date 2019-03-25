.. R for Data Science documentation master file, created by
   sphinx-quickstart on Thu Feb 21 13:59:58 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to R for Data Science's documentation!
==============================================

Welcome to R for Data Science, a collection of tutorials designed to get students up and running in R even if they have no prior experience with programming. These tutorials are designed to not only provide students with the ability to stitch together code to meet a goal, but also an understanding of the principles of programming in R to help demystify the tool, and improve student confidence in working in R and troubleshooting problems. 

The course is organized as follows:

:doc:`Introduction <introduction>`

In this first in a number of tutorials, we’ll cover the very basics of R: how to install R; how to do math in R; how to use variables; and basic data types.

:doc:`Vectors <vectors>`

This tutorial introduces a key object in R: vectors. It explains how to create different types of vectors, how to subset them, how to modify them, and how to summarize them.

:doc:`Dataset Basics <dataset-basics>`

This tutorial introduces datasets — “data frames” in R. Datasets can be thought of as a collection of vectors stored as columns. We’ll talk about how to create datasets and how to read them from file. We’ll also talk more conceptually about how datasets should be structured.

:doc:`Modifying Data <modifying-data>`

Being able to quickly modify datasets — using tasks like subsetting, sorting, extracting unique observations, renaming variables, dropping variables, and creating new variables — is critical. This tutorial explains how to easily do this in R with functions from the dplyr package.

:doc:`Merging & Appending <merging-appending>`

This tutorial explains how to combine datasets by merging or appending them. Merging means transferring columns from one dataset to another, while appending means transferring rows from one dataset to another.

:doc:`For Loops <for-loops>`

This tutorial explains how to write for loops — which can be useful when you want to iterate a process in R — and shows how to use for loops to carry out Monte Carlo simulations.

:doc:`Collapsing Data <collapsing-data>`

This tutorial explains how to find summary statistics for different categories in a dataset — what is often referred to as collapsing data. Like the tutorial on modifying data, the tutorial draws on a set of intuitive and elegant functions from the dplyr package.

:doc:`Wide & Long Data <wide-and-long>`

This tutorial explains the difference between long and wide form datasets, shows why it’s generally preferable to use long form datasets, and goes over how to convert datasets from wide to long form.


:doc:`Writing Functions <writing-functions>`

This tutorial explains how you can write your own functions in R. After explaining the basics, the tutorial dives into two data science applications for writing functions.

:doc:`Tables in R <tables-in-r>`

This tutorial explains how to create and export tables in R. It was originally designed for undergraduate students at Stanford who tend to use Word rather than LaTeX.



From Whom is This Course Designed?
----------------------------------

Assumed knowledge
^^^^^^^^^^^^^^^^^

This course assumes *zero* programming experience. None. If you can open a web browser, send emails, work in microsoft word, you have enough programming experience for this course. 

Topics
^^^^^^

The goal of this course is to teach a student enough about R to do serious data analysis. However, there are many "flavors" of data science these days, so it's worth emphasizing the type of data science this course is most designed to support. 

This course is designed to serve students who are interested in analyzing data to answer specific questions. For example, it is well suited for social scientists who wish to do statistical analyses of political or economic data, or people advising policymakers on the likely costs of different courses of action. In this kind of data science, analyses of data are usually "one-offs" -- the goal is to analyze a dataset to answer a specific question, not build software that will continuously analyze data on an ongoing basis. 

It is not well suited for people who wish to design programs that, as a part of their operation, analyze data. So if your interest is in writing an iOS app that analyzes user data to make restaurant suggestions, this is probably not the best resource. That kind of data science is closer to "software engineering" (the writing of software programs you plan to distribute to users), for which you will probably find better training in a traditional computer science curriculum.   

How should I take this course?
------------------------------

Each topic here is presented in two parts: a tutorial that provides instructional materials about the topic in question, and then a set of exercises to allow you to practice the skills you are learning. 

These tutorials will not generally be very long, and we **strongly** recommend that while you read through them you do so with an open programming session so you can just play around a little, trying out the things you learn. 

But the most important thing is for readers to do the exercisesat the end of each tutorial. The research on learning to program is exceedingly clear on this point: **the only way to learn to program is to actually program,** so the more time you spend playing with the tools we are using, making mistakes, and troubleshooting, the more you will learn.

Why R?
------

Why R? Because it's currently one of the two most-used programs in data science (the other being Python), which means there is a good chance you'll be called upon to use it when working in teams. Moreover, it's a much easier tool to get started with than a language like Python.

It is worth emphasizing that we're not learning R because it is necessarily the ``the best'' language. The reality is that there are *lots* of tools for statistical programming, and each has its own strengths and weaknesses (e.g. R, Stata, SPSS, Python, Julia, Matlab, etc., etc.). People often develop strong opinions about which language is *best*, and sometimes pass judgement on people who use other languages. Every programming language has its strengths and weaknesses, and what is "best" depends on your use-case (the types of things you are using the language to do). This is true not only because languages themselves have strengths and weaknesses, but also because the tools and packages that have been created for use in different languages differ (e.g. people just haven't made a good package for doing geo-spatial work in Julia yet, for example). And if you're working on teams, you'll also have to make decisions based on the backgrounds of your tool sets. All of which is to say: there is no single *best* language for all purposes. But R is a very popular, strong, general purpose language, so will serve as a great starting point.

As a result, over the course of your career you may find yourself gravitating to one tool or another as required by your research. But in providing you with a firm foundation in a very popular language like R, we feel confident that we will not only be providing you with tools that will allow you to do most everything you'll want to do in graduate school, but we will also be providing you with *generalizable* skills around data manipulation that you will find useful if you later change platforms.

To learn more about the differences between common programming languages, you can find a summary [here](http://www.programming4ds.com/html/languages.html). 


.. toctree::
   :hidden:
   :maxdepth: 1

   Introduction <introduction>
   Vectors <vectors>
   Datasets <dataset-basics>
   Manipulating Data <modifying-data>
   Merging <merging-appending>
   Collapsing Data <collapsing-data>
   For Loops <for-loops>
   Functions <writing-functions>
   Tables <tables-in-r>
   Reshaping <wide-and-long>

