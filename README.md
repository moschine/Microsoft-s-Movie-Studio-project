## Microsoft-s-Movie-Studio-project
# EXPLORATORY DATA ANALYSIS FOR MICROSOFT'S MOVIE STUDIO
## Introduction
With technology and the availability of vast and large amounts of data, companies are increasingly turning to exporatory data analysis techniques to gain insights into the market and have a proper understanding of the businesses they want to venture into and generate alpha. This project, aims to develop a predictive exloratory data analysis for micresoft's movie studio, using a range of data from different movie companies as inputs.

The project involves analyzing data from the zippeddata file to gain insight on market-specific factors such a movie reviews, ratings, annual domestic and foreign revenue, movie genres,and also movie budgets. This helped in developing and evaluating the performance of the selected key areas of interest. The results of the project could provide valuable insights into the microsoft's movie studio project and inform investment decisions both local and internationally.

## Main Objective
The main objectives for this analysis is to identify the types of films that are currently performing well in terms of their ratings, reviews and total annual revenue (both domestic and foreign) in the movies industry, and also to leverage the information from the insights of the analysis, into making a more informed decision, about Microsoft's movies studio production strategies.

## Notebook Structure
1. Reading the Data
2. Data Wrangling
3. Exploratory Data Analysis
4. Business understanding
5. Data understanding
6. visualization
7. Conclusions
8. Recommendations
9. Data Understanding
    
## Business understanding
### the head of Microsofts movie studio wanted to understand.

1. How the insights derived from the analysis of both the domestic and foreign gross revenue be translated into actionable strategies for entering and expanding into the international markets.
2. was there additional data sources that stakeholders believe could provide valuable insights to the audience preference, market trends, or competitor strategies.
3. In what ways can the tools and libraries utilized in the analysis enhance collaboration between our data analysts, filmmakers, and marketing teams to make more informed decisions.
Data understanding

### The data used in this project was a downloaded zippeddata folder containing the following files:

tn.movie_budget.csv
tmdb.movies.csv
rt.reviews.tsv
rt.movies_info.tsv
bom.movies_gross.csv
im.db
### The primary data for this analysis, was stored in the "im.db.zip"

The movie datasets used for this analysis were sourced from various platforms, including:

Box Office Mojo
IMDB
The Numbers
Rotten Tomatoes
TheMovieDB
Of the several datasets used, only some features and rows are relevant to the process such as: movie_basics,movie_ratings,from the **("im.db" SQL database tables)**. Data from the **"bom.movie_gross"** dataset was used to identify the top movies based on domestic and foreign gross.then the insights was used to visualize the information using horizontal bar plots and line graphs.
<img width="586" alt="image" src="https://github.com/moschine/Microsoft-s-Movie-Studio-project/assets/144592615/9c4aacba-17cd-4b16-b7fa-b07253d6706e">
<img width="615" alt="image" src="https://github.com/moschine/Microsoft-s-Movie-Studio-project/assets/144592615/239c8c77-9bc2-4bdd-8948-ff2d5614fec0">
<img width="551" alt="image" src="https://github.com/moschine/Microsoft-s-Movie-Studio-project/assets/144592615/dda0bfe7-3880-4348-8416-9faf3131dddf">

# Methodology
## 1. Data Wrangling
Out of the several datasets used, only some features and rows are relevant to the process such as: movie_basics,movie_ratings,from the ("im.db" SQL database tables). Data from the "bom.movie_gross" dataset was used to identify the top movies based on domestic and foreign gross.then the insights was used to visualize the information using horizontal bar plots and line graphs.Therefore, in this step, the features that were not required from each dataset were dropped.

## 2. Exploratory Data Analysis
Data collected, identified the movie with the highest rating, the top rated movies were analyzed, and a line plot of average ratings for, over the years was created Data explored data from Rotten Tomatoes, TMDB, and the "im.db"SQL database, specifically the "movie_basics" and "movie_ratings" tables.

## 3. Conclusions
Movie productions are majorly influenced by genres, release years, runtime and annual domestic and gross revenue. movie ratings and reviws are some of the key features to look into when learning how which types of movie genres are the best for production in the movie industry.
## 4. Recommendations
- Based on the analysis, Microsoft's movie studio, should consider focusing on the: genres, release years, runtime and annual domestic and gross revenue, that have historically resulted in successful films.
- Microsoft's movie studio and their financial analysts should leverage data science, exploratory data analysis techniques to generate more accurate and sustainable predictions.
- Microsoft's movie studio should consider, producing movies with description since foreign audience, may not be well aquinted to only english.

