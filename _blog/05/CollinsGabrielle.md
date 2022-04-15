---
author: "Gabrielle Collins"
title: "Renv for workflow issues"
layout: post
topic: "05"
short-topic: Fixing github actions
due-date: 2022-02-24
root: ../../
output: github_document
---

## Prompt:

Remember the github action disaster of blog #3? :)
This week, we will try to tackle the cleanup, and you write a paragraph or two about your experience with it. 

Read the vignette [Introduction to renv](https://rstudio.github.io/renv/articles/renv.html) for the `renv` R package by Kevin Ushey.

Then do:

1. **Install the R package `renv` on your local machine.**

2. **In the project for blog 3, initialize the workflow used by the `renv` package.**

3. **Add all dependencies to the environment (implicitly by installing all the depepndencies or explicilty by listing dependencies in a DESCRIPTION file).**

4. **Add the `renv` folder to your blog 3 repository, and push the changes.**

5. **Is the github action working? Read any potential error messages in the workflow and try to fix things. Make sure to check stackoverflow for help, don't forget our forum!**


Write a blog post addressing the following questions: 

1. **What is the idea of the renv package?**

The idea of the renv package is to limit your R environment to only dependencies you need, to help rid of any errors. It helps manage libraries and packages within your R project and helps create a reproducible environment. 

2. **In 50 to 100 words describe your experience working with `renv`. What went well? What did not go so well?**

The main issue I was trying to fix was rendering problem with my markdown file. Installing the 'renv' package went smoothly, and making minor edits to the yaml file was also relatively quick. The only issue I ran into was the ordering of code in my markdown file. Ultimately, what worked best was loading plyr, then dplyr, then initializing renv. After doing that, and pushing the new renv folder to my repository, my markdown file successfully rendered and the workflow run was completed successfully. 

Submit this blog post to the blog-5 repo. 

