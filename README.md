# Wine-Quality-Prediction
## Summary:
* Wine Quality prediction is an EDA of the Playground series data for season3 episode 5.
* This is an EDA of the Playground series data for season3 episode 5.
* The data is synthetic and ask to predict Wine Quality, with a range of 0-10. With 10 being a high-quality wine.
* This is a Multi-class classification problem
* The dataset for this competition (both train and test) was generated from a deep learning model trained on the original Wine Quality dataset.
* The metric required to be used by the competition is Quadratic weighted kappa
## Problem Statement (ML/DL):
1.	Objective: To predict the Quality of the wine on the range or scale of 0-10 with the help of the given features.
2.	Data: The dataset contains information on a different combination of chemicals used for making wine, with the columns names Id, fixed acidity, citric acid, residual sugar, free sulfur dioxide, total sulfur dioxide, ph, density, sulphates, alcohol along with Target Quality.
3.	Evaluation Metric: The model will be evaluated using Quadratic weighted kappa and for our understanding purpose we use the f1 score along with the confusion matrix.
4.	Constraints: The model should be able to run on a standard laptop with 8 GB of Ram and a standard CPU.
5.	Expected Result: The model should be able to predict the Wine Quality with an accuracy of at least 75%. 
## Workflow explanation:
* Problem definition: Defining the problem of predicting, here we need to predict the quality of the wine with the given information and identifying the appropriate machine learning techniques to use.
* Data collection and preprocessing: Collecting and preparing the Wine Quality dataset from the playground series data for season 3 episode 5. This includes tasks such as cleaning, transforming, and normalizing the data.
* Exploratory data analysis (EDA): Analyzing the data to understand its chemical property in identifying the quality of the wine and identify patterns and trends. This includes tasks such as visualizing the data, calculating summary statistics, and in this data we don’t have the missing values and duplicated values.
* Feature engineering: Creating new features or transforming existing features to improve the performance of the model. This includes tasks such as creating new features based on the existing data, encoding categorical variables, and scaling numerical variables.
* Model selection and training: Selecting an appropriate machine learning model and training it on the data. This includes tasks such as selecting the appropriate algorithm, tuning the model's parameters, and evaluating the model's performance.
* Model evaluation: Evaluating the performance of the model using appropriate evaluation metrics such as  precision, recall and f1-score.
* Model Tuning: Try to reduce the overfitting or underfitting on the select model and get the best estimator and best parameters. And Create a new model with the best estimator and predict 
* Final Prediction on the Test (Unseen data): After identifying the best hyperparameter-tuned model, now predict the results from the finalized model
