# Bulldozer_price_prediction-Regression---Kaggle-Competition-
The problem definition of this project is to predict the sale price of  bulldozers by their previous sales attributes. This project is one of the problem that kaggle competition community posts.

Initially, we load the data that is downloaded from kaggle.

We follow a framework with 6 steps in every machine learning project:

Here are the steps invloved in the project:

1. Problem Definition:
 
2. Data

3. Evaluation

4. Features
 
5. Modelling

6. Experimenting


1. Problem Definiton:

How well can we predict the future sale price of a bulldozer, given its characteristics and previous exapmles of how much similar bulldozers have been sold for?

2. Data:

 https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

3. Evaluation:

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

4. Features:

Viewing and analysing the features and thier relations

5. Modelling and Experimenting:

-->According to the machine learning models, data need to be in numerical form, so we turn string types into category type and then numeric type. After turning every column into numeric type, we fill the missing values.

-->Now, we split the data into training and validation sets and try to fit the RandomForestRegressor and calculate the evaluation metrics.

-->We tune the hyper parameters with RandomizedSearchCV and find the best parameters to build ideal model.

-->In this project, we turn the test data set into numeric type just as we have done to training set. And predict the values using the ideal model that we built before.

-->Finally, we calculated the importance of each feture and drew a plot.
