# Loan-ML-Models

The objective of this project is to build a model to predict if a loan will be paid off or in collection.

In this notebook, we load a dataset using Pandas library, and apply the classification algorithms, using the training set to build the most accurate model for this specific dataset by accuracy evaluation methods.

This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| Loan_status    | Whether a loan is paid off or in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |


We'll use the following algorithm:

- K Nearest Neighbor(KNN)
- Decision Tree
- Support Vector Machine
- Logistic Regression

We'll use either <strong> scikit-learn </strong> and <strong> Numpy libraries </strong> for developing the classification algorithms.

In order to build the models we'll use the loan_train.csv and we'll test them using the loan_test.csv
