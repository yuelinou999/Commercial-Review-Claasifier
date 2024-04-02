# Commercial-Review-Claasifier
This project is mainly using ANN model to identify the fake/AI generated reviews database over 500k+ for products sold online, and find the business insight from the data.

We initiated this project from the data-preprocessing, which included over 500k+ datarows and 30+ attributes, feature engineering, ML model validation, and data-driven strategy.

We removed over 500+ duplicate values, handed over 2000+ missing values, and correct values. Performing feature scaling through standardization and normalization, and process ordered categorical data with Ordinal Encoding to enhance the model's predictive capability. 

We selected 4 models for the training and optimization, which included: regression model, CNN, RNN, and LMTS. We divided the database into a training set and testing set (8:2). Sensitive Model to seperate review's classifier to 5 different levels, random forest model healps us increaced accuracy. The Hyperparameter Tuning was conducted through Random search and Grid Search. Then, we used cross-validation to evaluate the models and ensure that there was no overfitting. The ANN model based on the F-1 score, which reached 0.41, is most fit for our case.
