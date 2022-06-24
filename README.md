# Autism Prediction

This was another Kaggle competition in association with Reva University and Swiss Re. In this competition competitors was expected to build a classifier which can  predict whether a person has Autism or not.

In this challenge first I performed some exploratory data analysis to derive insights from it regarding how different factors affect whether a person has autism or not.
Data provided in this competition was not a standard one so, I have performed Data Cleaning as well before performing the data Analysis. Data Imbalance was also one of the challenge which was supposed to be handled by the competitors.

I used LogisticRegression, Support Vector Machine and XGBoostClassifier from the sklearn library but the performance achieved by LogisticRegression was <code>85%</code> along with the validation accuracy of <code>82%</code> which implies that the model is not overfitting the data was able to generalize well on the training data.

By using this model's predictions I scored <code>88%</code> accuracy on the test data and secured **9th** position out of 120 competitors in this competition.

![image](https://user-images.githubusercontent.com/77848178/175614444-98b7af07-fcdc-43b2-b98a-42aa0b49bdb2.png)

Checkout my Jupyter <a href='https://www.kaggle.com/code/abhishek123maurya/autism-prediction-by-ai' target='_blank'>Notebook</a> on kaggle for a better readable interface.

Thankyou for reading.
