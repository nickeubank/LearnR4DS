# R for Data Science Repo


Repo for data science tutorials.

Sphinx is a python based document builder. When you ask it to update, it will:

- Run all jupyter notebooks that have changed since last run
- Update indices and table of contents
- Create new HTMLs

So if you make changes in a jupyter notebook and you want it on the site, just save changes and:

- Navigate to repo folder from command line
- type `make html`
- commit and push changes.

The only non-jupyter notebook content is `source/index.rst`, which has a markdown syntax. That's the homepage.
