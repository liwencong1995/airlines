airlines
================

[![Travis-CI Build Status](https://travis-ci.org/beanumber/airlines.svg?branch=master)](https://travis-ci.org/beanumber/airlines)

This package contains information from the US Bureau of Transportation Statistics about flights, and provides functionality for uploading multiple years worth of data to an SQL database. To help understand what causes delays, it also includes a number of other useful datasets:

-   `planes`: construction information about each plane
-   `airports`: airport names and locations
-   `airlines`: translation between two letter carrier codes and names

The data in the [nycflights13](http://github.com/hadley/nycflights13) package is a special case of `airlines` for the year 2013, and all outgoing flights from the three New York City airports (LaGuardia , JFK, and Newark). This `airlines` package will allow you to download data for over 160 million flights from 1987 to present, from all US airports.

This package uses the [etl](http://github.com/beanumber/etl) database framework.

Please see [the vignette](https://github.com/beanumber/airlines/blob/master/vignettes/intro.Rmd) to get started.
