# Movie Producer Seeks Film Analysis

![crop movie night](https://github.com/user-attachments/assets/6dbff912-977c-4880-8c51-0f47dd23c785)

__Autor__: [Joshua G Grimes](https://www.linkedin.com/in/joshua-g-grimes/)

## Overview
This project analyzes the movie data from the [Internet Movie Database (IMDB)](https://www.imdb.com/) and [Box Office Mojo](https://www.boxofficemojo.com/) in order to determine what type of films are currently doing the best at the box office. A descriptive analysis of domestic box office sales determines that specific studios, genres, and movie lengths are more successful than others.

## Business Problem
![box office](https://github.com/user-attachments/assets/9d252eae-7f4b-42be-8d18-3011211a7bf6)

A company is looking to expand into the movie business. They don't know anything about creating movies so they have hired me to to a descriptive analysis of the film industry. They want to know what types of films are currently doing the best at the box office. Using the movie data from the IMDB and Box Office Mojo, I describe patterns in the amount of domestic ticket sales movies made from 2010 to 2018 based on the studio that made the movie, the movie genre, and the length of the movie as the definition of success at the box office.

## Data
![IMDB_Logo_2016 svg](https://github.com/user-attachments/assets/664caea3-8c33-487c-acc8-b0f3f6a3f191)

IMDB is an online database of information related to films, television series, podcasts, home videos, video games, and streaming content online. The data contains information including cast, production crew, plot summaries, trivia, ratings, and reviews. Box Office Mojo is a website that tracks box-office revenue in a systematic, algorithmic way. The database I have contains 73,000 entries for movies from 2010 to 2027. The database contains 9 tables with various information including: movie_id, primary_title, start_year, runtime_minutes, genres, averagerating, numvotes, title, regions, etc. The data from Box Office Mojo is in a csv format and contains 3,000 entries for moves from 2010 to 1018. The data from Box Office Mojo contains: title, studio, domestic_gross, foreign_gross, and year. These data are suitable for this project because the company is interested in knowing which films are doing the best at the box office and I have how much money the movies made at the box office and I have other data I can filter and sort by to find patterns in which characteristics of movies made the most money.

## Methods
This project uses descriptive analysis to provide useful insights into domestic movie sales. 

# Results
#### Movie Sales by Studio
Buena Vista made 22 billion more than the next closest studio from 2010 to 2018. 

![Movie Sales by Studio](https://github.com/user-attachments/assets/b53aa472-7c4d-4fee-83cc-23ff4d7e21dd)

#### Movie Sales by Genre
Action films made 62 billion more than the next closest genre from 2010 to 2018. 

![Movie Sales by Genre](https://github.com/user-attachments/assets/9c9d9810-3e02-4e0e-a857-a49e600ba038)

#### Movie Sales by Runtime
Movies between 100 and 119 minutes made 29 billion more than the next closest runtime from 2010 to 2018. 

![Movie Sales by Runtime](https://github.com/user-attachments/assets/5a78de86-9e31-46b1-9a5f-bd11e25ba8ea)

## Conclusions
This analysis leads to three recommendations for the company to produce. 

- __Produce a movie using the Buena Vista Studio.__ Buena Vista studio earned *22 billion* more in domestic income than the next closest movie studio.  They have a best record of success at the box office during the study period.

- __Produce an action movie.__ Action films made *62 billion* more in domestic income than the next closest movie genre.  They have the best record of success at the bo office during the study period. 

- __Produce a movie between 100 and 119 minutes long.__ Movies produced with a runtime between 100 and 119 minutes earned *29 billion* more in domestic income than the next closest runtime category.  They have the best record of success at the box office during the study period. 

## Next Steps
Further Analysis could yield additional insights into which movies have the highest domestic sales: 

- __Better understanding of the cast and crew.__ Modeling the impact of high level production crew and cast on the success of the film. 

- __Production Budget__ Analysis of the net budget of the film may give a better understanding of success. Is it better to spend a large budget on the production of the film and have a high income or to spend a small budget and make a smaller income.  Is there a relationship between budget and income? 

- __Advertising__  What does the role of advertising money play in the success of the movie?  What type of advertising produces the largest return? 

## More Information

See the full analysis in the [Jupyter Notebook](https://github.com/josh-g-grimes/Film-Review/blob/main/notebook.ipynb) or review this [presentation]()

For additional info, contact Josh Grimes at josh.g.grimes@gmail.com

## Repository Structure

|--- .gitignore

|--- README.md

|--- notebook.ipynb

|--- presentation
