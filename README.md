# The Impact of Pricing and Ratings on Video Game Popularity
DSA210 Term Project / Spring 2025-2026 

Student: Artun İşler

## Motivation 

My primary reason for choosing this project is my interest in video games and my future plans related to the gaming industry. Games have become an indispensable part of the entertainment industry today, and many people (including myself) turn to this sector to fill their free time.

The fact that most high-quality games are paid has led me to question the impact of price on a game's success. For this purpose, I want to investigate how a game's price and user ratings affect its popularity and perceived quality.

This project aims to analyze whether high-rated and high-priced games are actually more popular, and whether price and rating factors play a decisive role in game success. I also aim to analyze the influence of other factors on popularity in this project.


## Popularity description
- 

## Data Sources 
### 1) Steam Games Dataset 
- The primary dataset contains information on over 120,000 games. It includes key variables such as game name, genre, price, release date, and, most importantly, the number of user reviews. In this project, the number of reviews is used as the main indicator of popularity, reflecting how many players have interacted with a game.
   
- Link: https://www.kaggle.com/datasets/fronkongames/steam-games-dataset


### 2) Video Games Sales 
- The second dataset consists of approximately 17,000 records containing information on global sales figures, platforms, and genres. By correlating popularity with commercial success, this dataset provides a broader perspective, allowing for comparisons between player engagement and actual market performance.
  
- Link: https://www.kaggle.com/datasets/gregorut/videogamesales


### 3) Steam Spy API
- The third dataset  provides information such as estimated ownership rate, average playtime, and the distribution of positive and negative reviews. These variables make it possible to understand player behavior and interaction more deeply, and are particularly useful for analyzing factors such as playtime and ratings.

- Link: https://www.kaggle.com/datasets/muhammadaqeelkabir/steam-games-dataset-steamspy-api

In this project due to size issue of files, they cannot be uploaded directly. Therefore, links to the files are provided below their respective descriptions.


## Data Collection 
- Step 1: The datasets are downloaded manually and uploaded into Google Colab. Each dataset provides different types of information, such as game prices, user reviews, playtime, and sales figures.
- Step 2: After the datasets are loaded, inconsistencies in the datasets are corrected. For example, column alignments are corrected and it is ensured that game titles are in the correct format. Missing and irrelevant values ​​are removed, and only the necessary columns are selected for further analysis.
- Step 3: The SteamSpy and Video Game Sales datasets were cleaned and reduced to usable rows. These datasets were then merged with the main Steam dataset, categorized by game title.
- Step 4: After merging, in the final step, additional variables such as total_reviews, price categories, rating (derived from positive and negative reviews), and popularity_rank are created.


## Exploratory Data Analysis (EDA)
In this project, the analysis focuses on the following aspects:

 - The distribution of game prices and popularity (review counts)
 - The comparison between free and paid games in terms of popularity
 - The effect of different price categories on popularity
 - The relationship between playtime and popularity
 - The impact of game genres on popularity
 - The relationship between rating (user score / review ratio) and popularity


## Hypothesis
 - H1: Free games are more popular than paid games.
 - H2: Popularity differs across different price categories.
 - H3: Games with longer playtime are more popular.
 - H4: Game genre has an effect on popularity.
 - H5: Higher-rated games are more popular.

