# UC-Berkeley-AI-certificate-Module-20
capstone project initial report

Initial report summary

OVERVIEW

This is to analyze and predict wheater the customer will stay in the program. Customers who left within the last month – the column is called Churn. Two objectives.
1.	Analyze which factor affect the churn score the most.
2.	Build a model to predict the churn score so that the company can do something to keep the customer.

Data analysis summary

While the intuitive analysis on the plots can give us some rough ideas of each feature's importance, the correlation analysis can give us numerical evaluation of each feature influence, either positive correlation (toward churn score 1), or negative correlation (toward churn score 0).
•	In general, long tenure customers, 2 year contracts will stay longer with the program.
•	The customers without internet will stay longer, and on the opposite, the customers with fast fiber internet more likely to leave.
•	When the monthly charges is below $60, churn score is low, and then increases from $60 to $100. And then decrease after $100. It means the low income and high income will more likely stay.
•	Autopay will help keep the customers, and electronic check lead to high churn score. Surprisingly, the very traditional payment method, mailed check, lead to low churn score.
•	Paper billing lead to higher churn score. The company should encourage electronic billing to keep the customers and also save mailing cost.


Initial Report and Exploratory Data Analysis (EDA)

•	The features of the churn data set are analyzed through the plots and correlation analysis. The tenure, contract length, internet service and monthly charges play important roles in the churn score.
•	The data is cleaned and transformed for ML models. A Logistic Regression model is used for the initial training and prediction as the baseline. Its accuracy is about 80%.
•	More models will be tuned with grid search and compared for the final report. We expect to develop a model with 95% and higher accuracy so that the telecommunication company can do some special promotions to keep the customers with high churn scores.

