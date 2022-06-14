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

Linear Regression and Random Forest Regression were used before settling on ________.

*Model Evaluation and Selection*

 EXPLAIN MODELS HERE

### Communication

Please see the attached PDF in the github repo for the presentation.
