# IMDb-scraper
> Data scraper for scraping IMDb.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Installation](#installation)
* [Code Examples](#code-examples)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
This scraper let's you scrape movies from IMDb based on genre. Information stored about each movie: title, year, duration, rating, genres, plot, IMDb rating, url to poster.

## Technologies
Project is created with:
* Python 3.9.0
* BeautifulSoup4

## Installation
1. Install the package using pip:
```
pip install git+https://github.com/dovilez/IMDbscraper
```
2. Import the scraping module:
```
from scraping import scraping
```

## Code Examples
Specify the genres and number of movies to scrape, then use collect_keywords function:
```
genres = ['action', 'comedy', 'sci-fi', 'horror']
number_of_movies = 100
df = scraping.collect_keywords(genres, number_of_movies)
```


## Status
Project is: _finished_

## Inspiration
Project created as a task for DS.2.4 project.

## Contact
Created by Dovilė Žaltauskaitė [@dovilez] 
