# IMDb Web Scraping Project and Film Recommender

A data analysis project with the aim of attaining data through web scraping and creating a film recommender
## The Problem and Objectives

The main aim of this project was to develop the skill of web scraping, learn how to work with html and extract data from the internet for my own analysis.

IMDb is a large and comprehensive film and TV webiste, which offers ratings and reviews in order to guide recommendations. I wanted to use this webiste to colect data about the top 1000 films according to their IMDb movie rating, with the purpose of analysing it and creating my own film recommender using Python.
## Solution Strategy

The solution for this project will involve the building of a function able to scrape the IMDb webiste for relevant film information, such as IMDb Rating, film runtime and genres, to then analyse and create a film recommender.

Step 1 - Data Collection: In this section I will find a webpage on the IMDb webiste where I can sort films by the top IMDb Rating and scrape data about the top 1000 films by setting up a web scraper function using Python.

Step 2 - Data Preparation: In this section I will first wrangle all of the data into one Pandas dataframe ready for analysis. After this I will clean the data making sure all nulls and duplicates are dealt with and data types are all in order.

Step 3 - Exploratory Data Analysis: In this section I will analyse different aspects of the data, depending on what I am able to acquire from the IMDb website. My plan is to look into the relationships between film runtimes, genres and age ratings and how this affects IMDb Rating and also the profit the film makes.

Step 4 - Film Recommender: This section will have the aim of creating a film recommender, where the user is able to input what genre, runtime and year of film they are looking for, and produce top 3 recommendations based off the IMDb Rating of the film.
## Top 3 Data Insights

- Film ratings seem to decrease over the past 20 years

![Alt text](https://github.com/mattyh1010/IMDb-Web-Scraping-Project/blob/main/films_through_time.png)

- More family friendly and less restrictive age ratings seem to perform better in terms of film rating and gross profit

![Alt text](https://github.com/mattyh1010/IMDb-Web-Scraping-Project/blob/main/age_rating.png)

- The same can be said for film unique genres and also genre pairs. More family and child friendly genres such as Family, Adventure and Animation perform the best in terms of film rating and gross profit

![Alt text](https://github.com/mattyh1010/IMDb-Web-Scraping-Project/blob/main/genre.png)

![Alt text](https://github.com/mattyh1010/IMDb-Web-Scraping-Project/blob/main/genre_pair.png)
## Film Recommender

Example of film recommender, which takes user input about genre, year and runtime of film the user wants to watch and gives the top 3 recommendations

![Alt text](https://github.com/mattyh1010/IMDb-Web-Scraping-Project/blob/main/film_recommender.png)
## Conclusions

My main aim of upskilling in web scraping data was a success and I now have the ability to collect a wider variety of data for future projects.

Some interesting insights from limited data collected, seems to be a pattern around films that are more family friendly and suitable for children performing better in terms of IMDb rating and gross profit. Perhaps cause for further analysis into the dip in film ratings in the past 20 years.

