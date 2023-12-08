# **Microsoft Movie Studio Analysis**

## Overview
This project aims to provide guide for decision making for Microsoft Movie. It analyzes three datasets using python and the findings are that animated genre produce highest net profit, the more the production budget there's a tendency that the net profit would increase too.


## Business Problem
Microsoft has a new movie studio and would like to produce movies that would bring in profits and enjoyed by the audience. The objective is to gain comprehensive insights into the characteristics and genres that resonate most with audiences.
## **Questions for analysis**
1. <span style = "color: #ff914d">which genre is more profitable?</span>
2. <span style = "color: #ff914d">What is the ideal budget production?</span>
3. <span style = "color: #ff914d">How long movies should be?</span>

## Datasets
Three datasets are used in this project:
1. Internet Movie Database (IMDB)
  > It contains multiple tables but the tables of interest are **<span style = "color: #ff914d">movie_basics</span>** and **<span style = "color: #ff914d">movie_ratings</span>** where the ***averagerating*** and ***runtime_minutes*** will be used to determine the ideal length of movie.

2. The Numbers (TN)
  > TN dataset contains 5,782 records and  6 columns. The column of interest are production budget and worldwide gross. This will enable us to calculate the profit and investigate on Return on Investment.

3. The MovieDB (TMDB)
 > TMDB dataset contains 26,517 records and 9 columns. Genre_id column is used to map genre of the movies, to find which genre is more profitable.


The TN and TMDB datasets are merged after dropping unnecesaary columns and missing values. Analysis like Net profit, Return on Investment and finding profitable genre is performed using this dataset.Scatter plots and bar graphs were used to visualize the findings. In calculating ROI median is used due to presence of outliers.

## Findings
1. Animation was the most profitable genre.
2. High buget movies generate huge profits.
3. Ideal length of movie liked by audience ranges from 80 to 90 minutes.

## **Conclusions**

1. - **Produce movies within the Animation genres**.
    
2. - **Invest in High Budget movies**.
    
3. - **Make movies length near 90 minutes**.
    
