# WTA_project

### Abstract

The goal of this project was to use regression to see if it was possible to create a model that took numerical and categorical aspects of hikes in Washington State and would be able to predict the user based rating. This model would be useful for backend engineers looking to create recommendation systems for newly added or newly built trails. I worked with data that was scraped from the Washington Trail Association website (wta.org) using both linear regression and ridge regression to create a model and find the features that were most relevant in user ratings.

### Design

This project comes from my own interest in Washington Hikes and my time as a former employee of the Washington Trails Association. The goal of this project is to find if there is any relationship between hike features and user ratings via regression models. This project would be useful to backend engineers as was stated in the Abstract, but also could be used by users who would like to see what characteristics the general public thinks make a good hike.

### Data

This dataset contains 3935 Hikes, with 19 Features, where 3 are numerical. Some features include length, gain, lakes, old growth, and Coast. A few other features were created in order to experiment and create features that increase the model's score.

### Algorithms

*Feature Engineering*

1. Converting many categorical datapoints in binary dummy variables.
2. VADER sentiment analysis on written summary.
3. Latitude and Longitude for hikes.
4. Removing NA values and subsetting features based on model scores.

*Models*

Linear Regression and Random Forest Regression were experimented before settling on a Random Forest Regression model which was tuned using Grid Search CV. This model was able to give an R<sup>2</sup> ~ 0.58 on the Train data and R<sup>2</sup> ~ 0.57 on the Test set. The best results were achieved by subsetting the data by the number of ratings > 10 and the features that impacted the Random Forest Regression the most. The R<sup>2</sup> is not high, and the Random Forest Regressor has low interpretability, so it is difficult to see which features had the most impact on the model. The Linear Regression model preformed quite poorly, the best R<sup>2</sup> achieved was about 0.2. The numerical data was not linear with respect to the ratings and most of the model was explained by the B<sub>0</sub> coefficient, which was essentially the average rating.


### Communication

Please see the attached PDF in the github repo for the presentation.
