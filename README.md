# Marketing Analysis Using Machine Learning

This repository contains a marketing analysis project using machine learning techniques. The project aims to predict the success of marketing campaigns based on historical data.

## Project Overview

The goal of this project is to analyze marketing campaign data and build machine learning models to predict whether a client will subscribe to a term deposit. The dataset used for this project is the [Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/bank+marketing) from the UCI Machine Learning Repository.

## Data

The dataset contains information on various attributes related to clients, including their demographics, contact information, and past interactions with the bank. Key attributes include:

- `age`: Age of the client
- `job`: Job title
- `marital`: Marital status
- `education`: Education level
- `default`: Credit default status
- `housing`: Housing loan status
- `loan`: Personal loan status
- `contact`: Type of communication contact
- `month`: Last contact month of the year
- `day_of_week`: Last contact day of the week
- `duration`: Duration of the last contact in seconds
- `campaign`: Number of contacts performed during this campaign
- `pdays`: Number of days since the client was last contacted from a previous campaign
- `previous`: Number of contacts performed before this campaign
- `poutcome`: Outcome of the previous marketing campaign
- `emp.var.rate`: Employment variation rate
- `cons.price.idx`: Consumer price index
- `cons.conf.idx`: Consumer confidence index
- `euribor3m`: Euribor 3 month rate
- `nr.employed`: Number of employees

## Models Used

The following machine learning models were used in this project:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Gradient Boosting

## Results

The performance of each model was evaluated using the following metrics:

- Accuracy: The proportion of correct predictions out of all predictions.
- Precision: The proportion of positive predictions that were correct.
- Recall: The proportion of actual positives that were correctly predicted.
- F1 Score: The harmonic mean of precision and recall.

The `Gradient Boosting` model performed the best with the following metrics:

- Accuracy: 91.53%
- Precision: 67.12%
- Recall: 52.04%
- F1 Score: 58.62%


## Conclusion

This project demonstrates the application of various machine learning models to predict the success of marketing campaigns. The results show that Gradient Boosting achieved the highest performance metrics, indicating its suitability for this type of predictive task.
