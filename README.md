# Analyzing Music Globally - 2017 

## Overview

A brief analysis of Spotify’s top ranked songs around the world, throughout the year 2017.

Core Responsibilities: Presentation design, initial cleanup 
Tools used: Pandas, Jupyter Notebook, Matplotlib

## Hypothesis

Is there a travel pattern of how top hits move throughout the globe? 

(Does it become #1 in US first, then in Italy, then in Great Britan etc..)

## Questions & Ideas 

Finding what songs were ranked high throughout the year, and in which countries 

Time of year song remained at the top in a country

How long does a song stay in top 5 in a country?

When do the ranks start to shift?

Are certain songs ranked in the top simultaneously in multiple countries?

## Data Source 

https://www.kaggle.com/edumucelli/spotifys-worldwide-daily-song-ranking

![spotify_dataset.png](attachment:spotify_dataset.png)

## Data Exploration & Cleanup Process 

- Changed date column to datetime data type instead of object 
- Removed columns with no information
- Dropped URL column and renamed some of the columns to make it cleaner and more user friendly
- There is a “global” category under the country column that we used to find our overall top songs but it was then removed from further analysis
- When we say “Top” we mean ranked 1-5, mainly looked at Top songs and dropped the lower ranked songs

## Analysis Process 

1. Sort Functions & Groupby
    - how we created our graphs 
2. Breaking down most popular song for each person (point of analysis)
    - used excel to see if there were any overarching trends
3. Expanded observations to additional songs 
    - broke down data into sections
    - each section analyzed a song over a quarter out of the year, to find additional trends 
    - used multiple songs and combined quarter results 

## Challenges Faced

- Creating dataframes from our given data, for optimal results, in order to figure out whether we could prove or disprove our hypothesis with the data given  
- Realized that the release dates of songs needed to be taken into high consideration to explain the shift in streams and ranking over time
    (if a song was released mid year than it would not have data in the beginning of the year)
- Converted our data exploration into analyzing quarters of the year 
- Needed to add more months on each sides of the quarter to actually show the increase and decrease in popularity, from both sides 


## Conclusions 

Our hypothesis was disproved 

Numerical summary - the greatest number of streams of a song took place over a period of 3 months 

- We picked top three songs that had the highest streams in each quarter. 
- To show that it lives approx. 3 months, we picked months before or after, depending on the availability of the data


![Picture1.png](attachment:Picture1.png)


## Implications of Findings 

- Unfortunately did not find what was expected, some sort of travel pattern showing how song popularity travels around the globe 

- What WAS found was that songs stay popular for a certain period of time

NEW IDEA: maybe these songs are staying popular during a certain few months because the type of song relates to the timing of the year? 



![Picture2.png](attachment:Picture2.png)

## Story - Holiday Music  

During the holiday months of November and December the charts are mostly filled with Christmas and holiday music, resulting in the knock of other music to the bottom of the charts. 

On Christmas Eve, “All I Want for Christmas Is You” was streamed roughly 720 million times. 


![Picture1.png](attachment:Picture1.png)


```python

```
