# Assignment: NEWSAPI

An assignment which leverages NEWSAPI. A news api for getting breaking news headlines and searching articles from news sources and blogs around the world.

## directions for use

- fork this repo
- version control your progress in your personal repository.
- add your documentation to the docs directory
- when you are ready to let us see, add our github users to your repository

**We're Rooting for you** :+1:

![We are rooting for you.](images/rooting4you.webp)

## Problem Statement

As part of a data gathering exercise, which would back both operational analytics and machine learning.
Your team is tasked with **building a database of news paper articles released in the last week across europe** by leveraging the free [NEWSAPI](https://newsapi.org/) as a POC.

You will need to build a prototype, **hybrid datalake with a mysql database and blob storage**. It should service two main user categories,
namely analytical users and large scale AI algorithms.

Extra points will be awarded for:
- :chart_with_upwards_trend: **diagrams**. "A picture is worth a 1000 words" 
- :clipboard: *detailing the key requirements* of `analytical users` and `AI algorithm` usecases
- :heavy_plus_sign: **Adding** value with additional **features**. For example `notable persons` and `topics covered`.
- :large_blue_diamond: A short exploration on **ethical API querying practices** in the context of this work.
- :rocket: detailing the **deployment infrastructure** for this solution, incl. workflow diagram, implementing effective version control.
- 🧠 your **insights and discoveries** from this exercise.
- :fast_forward: possible **next steps**.


#### What is expected?

- a set of data pipelines
- final data is to be presented in a set of tables stored in mysql
- ethical API querying practices
- resources (e.g. databases) should be containerized. Think docker.
- code should be well documented with doc-strings and comments.
- code running environment to be virtualized or containerized.

#### Assumptions

- blob storage can be simulated by a local file-system.
- code should run on linux or mac like file-system.

#### Last Words

![itsAboutTheJourney](images/itsAboutTheJourney.webp)

## References

- [newsapi free api usage quotas](https://newsapi.org/pricing)
- [newsapi python api](https://newsapi.org/docs/client-libraries/python)
