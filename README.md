# Movie-Box-Office-Predictions
Project Overview

This project aims to predict movie revenue using data analysis and machine learning techniques. Through an in-depth analysis of a movie dataset, we employed visualization methods to showcase the features of the data and applied a Random Forest regression model to predict revenue. The process includes data cleaning, feature engineering, model training, and result output, ultimately generating the prediction results.

Main Steps and Techniques

1.Data Import and Basic Analysis
Import the movie training set and test set data (film_train.csv and film_test.csv).
Use the count() method to perform an initial check on the data to ensure data integrity.

2.Data Visualization

Distribution of Movie Languages:

Analyze the original languages of the movies using grouping and counting, and plot a bar chart to display the number of movies in each language.

Popularity and Income Relationship:

Draw a scatter plot to show the relationship between popularity and income.

Count the number of movies by country:

Parse the production_countries column, extract the main production countries, and draw a horizontal bar chart of the number of movies in the top 20 countries.

Count the number of movies by company:

Parse the production_companies column, extract the major production companies, and draw a horizontal bar chart of the number of movies by the top 20 companies.

3.Data Preprocessing

Feature Selection:

Select features and target variable (revenue) from training and test sets. Remove columns not relevant to the analysis such as genres, production_companies, etc.

One-Hot Encoding:

Perform one-hot encoding on the original_language column to convert categorical variables into numerical format, making them suitable for machine learning models.

4.Model training and prediction

Using the random forest regression model:

Create a pipeline containing an imputation and a random forest regression model, handle missing values ​​and train the model.

Generate prediction results:

Predict the test set and output the prediction results, including the movie ID and predicted revenue.






