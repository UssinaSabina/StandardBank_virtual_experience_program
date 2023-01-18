# StandardBank_virtual_experience_program
## About the programme:
During this programme, participants get the opportunity to step into the shoes of a Standard Bank team member and complete tasks that replicate the work that Data Science team does every day. The goal is to learn how to understand the data science project lifecycle, course train a model, and present the process as it relates to business objectives.
## Data Science With Python: Predicting Loan Defaults
**Business Problem:** Currently the home loan application process is a manual one. It which takes 2-3 days, which mean that the applicant will only be notified after 2-3 days of the application outcome.<br /><br />
**Business Objective:** Reduce the amount of time it takes for applicants to be notified about their loan statuses (to a matter of seconds).<br /><br />
**Hypothesis:** Based on historical data we can use machine learning to predict the loan status of a potential borrower such that the time taken for them to receive their respective statuses is reduced significantly. <br /><br />
**The process:**
1) EDA: manually and using AutoEDA Python libraries
2) Data preparation
3) Train and test different models
4) Present insights (PowerPoint presentation)<br /><br />
**The Metrics:** Accuracy Score and the ROC AUC Score.<br /><br />
**Modeling:** This problem is a binary classification as we are predicting two classes - approval or declination of a loan. We tried 4 different models: Random Forest, Support Vector Machines, AdaBoost, Gradient Boosting. After training the selected models, we chose Random Forest and by performing hyperparameter tuning we obtained 86,2% accuracy score.<br /><br />
**Conclusion:** The Random Forest Classifier has given us the best results.<br /><br />
# Repositoy Guide
**Notebook**<br /><br />
https://github.com/UssinaSabina/StandardBank_virtual_experience_program/blob/main/Predicting%20Loan%20Defaults.ipynb <br /><br />
**CSV files**<br /><br />
Train: https://github.com/UssinaSabina/StandardBank_virtual_experience_program/blob/main/CSV_files/train.csv <br /><br />
Test:  https://github.com/UssinaSabina/StandardBank_virtual_experience_program/blob/main/CSV_files/test.csv <br /><br />
