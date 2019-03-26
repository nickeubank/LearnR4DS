.. R for Data Science documentation master file, created by
   sphinx-quickstart on Thu Feb 21 13:59:58 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Learn R for Data Science!
=========================

Welcome to Learn R for Data Science, a collection of tutorials designed to both get students up and running in R quickly, and also provide a rich understanding of how and why R works the way it does. 

These tutorials begin with the assumption readers have **zero**  programming experience. If you can use google and download programs, you have all the experience required -- just head over to :doc:`Introduction <introduction>` and get started. If you have more experience, you can also jump ahead. 

For more on the philosophy behind these tutorials, suggestions on how to get the most out of them, or just more information on where they came from, check out the :doc:`About This Site <about-this-site>`. 

**Warning:** As of April 2019, this site is still very much a work in progress! Feel free to submit comments `here <https://github.com/nickeubank/LearnR4DS>`_

Course Organization
-------------------

:doc:`Introduction <introduction>`: In this first in a number of tutorials, we’ll cover the very basics of R: how to install R; how to do math in R; how to use variables; and basic data types.

:doc:`Vectors <vectors>`:  This tutorial introduces a key object in R: vectors. It explains how to create different types of vectors, how to subset them, how to modify them, and how to summarize them.

:doc:`Dataset Basics <dataset-basics>`: This tutorial introduces datasets — “data frames” in R. Datasets can be thought of as a collection of vectors stored as columns. We’ll talk about how to create datasets and how to read them from file. We’ll also talk more conceptually about how datasets should be structured.

:doc:`Modifying Data <modifying-data>`: Being able to quickly modify datasets — using tasks like subsetting, sorting, extracting unique observations, renaming variables, dropping variables, and creating new variables — is critical. This tutorial explains how to easily do this in R with functions from the dplyr package.

:doc:`Merging & Appending <merging-appending>`: This tutorial explains how to combine datasets by merging or appending them. Merging means transferring columns from one dataset to another, while appending means transferring rows from one dataset to another.

:doc:`Plotting <plotting>`: Plotting in R

:doc:`For Loops <for-loops>`: This tutorial explains how to write for loops — which can be useful when you want to iterate a process in R — and shows how to use for loops to carry out Monte Carlo simulations.

:doc:`Collapsing Data <collapsing-data>`: This tutorial explains how to find summary statistics for different categories in a dataset — what is often referred to as collapsing data. Like the tutorial on modifying data, the tutorial draws on a set of intuitive and elegant functions from the dplyr package.

:doc:`Wide & Long Data <wide-and-long>`: This tutorial explains the difference between long and wide form datasets, shows why it’s generally preferable to use long form datasets, and goes over how to convert datasets from wide to long form.

:doc:`Writing Functions <writing-functions>`: This tutorial explains how you can write your own functions in R. After explaining the basics, the tutorial dives into two data science applications for writing functions.

:doc:`Tables in R <tables-in-r>`: This tutorial explains how to create and export tables in R. It was originally designed for undergraduate students at Stanford who tend to use Word rather than LaTeX.

Questions, Comments, or Suggstions?
-----------------------------------

Please let me know! You can reach me `here <mailto:nick@nickeubank.com>`_, or submit an issue on the `github repository <https://github.com/nickeubank/LearnR4DS>`_ where the source material for this site is maintained. 



.. toctree::
   :hidden:
   :maxdepth: 2

   About This Site <about-this-site>
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
   Plotting <plotting>

