# Movie Box Office Gross Prediction
The objective of this project is to develop a predictive model that can estimate the box office gross revenue of movies based on various attributes and indicators. Two datasets have been used for the same, namely "tmdb_5000_movies.csv" and "tmdb_5000_credits.csv". These datasets have been prepared by scraping movie-related data from the IMDB website, covering a time span from 1916 to 2017.

To predict the revenue of movies, these datasets were utilized along with various machine learning models. This prediction can assist various stakeholders in the film industry, including production companies, distributors, and investors, to make informed decisions about resource allocation, marketing strategies, and revenue forecasting.

The project also focuses on data exploration, model interpretation, and practical application of the results. By accurately predicting movie box office gross revenue, the aim is to contribute to the understanding of the factors that influence movie success and provide valuable insights to stakeholders in the film industry.

For this project, the performance of four regression models (Linear Regression, Random Forest Regression, Gradient Boost Regression and Light GBM Regression) were compared. After evaluating the models on various metrics, it was found that Gradient Boost Regressor is the best performing model. It has the lowest mean squared, root mean squared and mean absolute error and the highest r2 score. The next best performing regressors are Light GBM, Random Forest and Linear Regressor respectively.
