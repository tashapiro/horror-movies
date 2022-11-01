

# Horror Movies :zombie:

## Overview

Purpose is to explore a dataset about horror movies dating back to the 1950s. Data set was extracted from **[The Movie Datbase](https://www.themoviedb.org)** via the tmdb API using R <code>httr</code>. There are ~35K movie records in this dataset.

## Workshop

This repository also supports content created specifically for the **Introduction to ggplot2** workshop organized the **[R-Ladies Paris](https://twitter.com/rladiesparis)**. Participants in the workshop create a total of 3 data visuals using ggplot2 and supporting ggplot libraries. Workshop material is in an **R Markdown html notebook** format. You can view the html file [here](https://tashapiro.github.io/horror-movies/code/ggplot-workshop).

The workshop is scheduled for 1pm ET October 13th, 2022. A recording of the session will be posted on YouTube at a later date.

**Workshop Materials**

- [Starter Notebook](https://github.com/tashapiro/horror-movies/blob/main/code/ggplot-starter.Rmd)
- [Solutions Notebook](https://github.com/tashapiro/horror-movies/blob/main/code/ggplot-solution.Rmd)

## Libraries Used

- tidyverse
- sysfonts
- showtext
- ggimage

## Data Dictionary

Note: for poster_path must be appended to this url https://www.themoviedb.org/t/p/w1280/ to generate full image!

| **Variable**          | **Type** | **Definition**             | **Example**                     |
|:---------------|:--------------:|:------------------|:---------------------|
| **id**                |   int    | unique movie id            | 4488                            |
| **original_title**    |   char   | original movie title       | Friday the 13th                 |
| **title**             |   char   | movie title                | Friday the 13th                 |
| **original_language** |   char   | movie language             | en                              |
| **overview**          |   char   | movie overview/desc        | Camp counselors are stalked...  |
| **tagline**           |   char   | tagline                    | They were warned...             |
| **release_date**      |   date   | release date               | 1980-05-09                      |
| **poster_path**       |   char   | image url                  | /HzrPn1gEHWixfMOvOehOTlHROo.jpg |
| **popularity**        |   num    | popularity                 | 58.957                          |
| **vote_count**        |   int    | total votes                | 2289                            |
| **vote_average**      |   num    | average rating             | 6.4                             |
| **budget**            |   int    | movie budget               | 550000                          |
| **revenue**           |   int    | movie revenue              | 59754601                        |
| **runtime**           |   int    | movie runtime (min)        | 95                              |
| **status**            |   char   | movie status               | Released                        |
| **genre_names**       |   char   | list of genre tags         | Horror, Thriller                |
| **collection_id**     |   num    | collection id (nullable)   | 9735                            |
| **collection_name**   |   char   | collection name (nullable) | Friday the 13th Collection      |



