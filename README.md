# IMDb Movie Ratings Analysis

## Project Overview

This project, conducted for my STATS 101A class at UCLA, explores the factors that influence IMDb ratings of movies. Using a dataset of 1,000 films with 16 variables, the study aims to determine which factors are most predictive of a movie's IMDb rating. The primary goal was to construct a predictive model that unveils the dynamics behind a movie's success as measured by its IMDb rating.

## Dataset

The dataset, sourced from Kaggle, consists of variables such as release year, Metascore, number of votes, gross revenue, and runtime. After a careful selection process, we focused on five key predictor variables:

- Released Year: The year the movie was released.
- Meta Score: A critical rating of the movie.
- Number of Votes: The number of IMDb users who rated the movie.
- Gross Revenue: The movie's gross earnings in U.S. dollars.
- Runtime: The duration of the movie.

## Methodology

The analysis began with a full model incorporating all selected predictors, followed by an evaluation of model fit and diagnostic plots. Despite attempts at transforming the model for better fit, the original model was retained due to its higher R-squared value. The final model revealed significant relationships between IMDb ratings and all selected predictors.

## Key Findings

- Older movies tend to have slightly lower IMDb ratings.
- Longer movies generally receive higher IMDb ratings.
- Higher Metascores and a greater number of votes are associated with higher IMDb ratings.
- Interestingly, movies with higher gross earnings tend to have slightly lower IMDb ratings, suggesting that commercial success does not always align with critical or audience acclaim.

## Conclusion

While the final model provides insights into the factors affecting IMDb ratings, it also highlights the complexities of predicting movie success, given the unpredictable nature of the film industry. Expanding the dataset to include additional variables such as economic factors, marketing efforts, and release timing could improve the model's predictive power.
