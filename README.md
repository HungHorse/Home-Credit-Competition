# Home-Credit-Competition

#Description of project
## Goal
This is a part of the Practice Project Capston class IS6812 at the University of Utah, David Eccles School of Business. This is my personal notebook for the project, but my team also include Linh Do, Ali Ladha and Sudeeptha Sivarajan. 

This competition originated from [Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data). Home Credit is a well-established lender operating primarily in the Southeast Asia region. While the region is developing rapidly, the personal loan market still lags behind that of more developed countries. This gap is largely due to a lack of formal credit history. In many cases, credit has been culturally overlooked or limited to informal arrangements between acquaintances or low-tier individual lenders. This pose as a lucrative market for many large credit lenders, that said if they could solve the problem of managing credit risk.

This is where our team comes in. With limited data points on borrowers’ credit history, we clean, train, and test a machine learning model that allows Home Credit to reliably expand its services to new borrowers and proactively manage its risk appetite.

## Datasets
The competition provided seven datasets, but for the purpose of our modeling and to optimize both training time and simplicity, we chose to focus on just two: application_train.csv and previous_application.csv.

## Outcome
Our champion model is a CatBoost classifier, which achieved an accuracy of 70% on the training dataset and a Kaggle score of approximately 70.
