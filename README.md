# Anomaly Detection: Supervised vs Unsupervised Techniques

Here you will find our project implementation of anomaly detection on credit card fraud dataset. This project was part of our evaluation and project work in DAT550 DATAUTVINNING OG DYPLÆRING.
This was a group project, by Alireza Hossein Zadeh Nik, Prava Thapa, Håkon Teppan and Sondre Tennø.

Github link: https://github.com/dat550-2021/Outliers

## Task

In this group project, we studied different supervised and unsupervised techniques on dataset of real-life transactions from an
international credit card corporation. due to imbalanced nature of the dataset, different kinds of under-sampling and over-sampling methods were conducted to make the training set balanced and their effect was compared for different supervised learning techniques such as random forest, logistic regression, K-nearest neighbour and NB classifier. For unsupervised learning, we experimented different algorithms like Isolation Forrest, One-class SVM, deep AutoEncoders, local-outlier factor and etc, and model performances were compared based on different metrics such as precision, sensitivity, and area under ROC curve.

## Dataset

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

To run this code, you will need to download the dataset from the kaggle competition:

https://www.kaggle.com/mlg-ulb/creditcardfraud

## Code

All of our code in this project are in one single jupyter notebook file, 'DAT550_Project.ipynb'.
Going through each section as they were implemented, download libraries, gathering data, visualization, supervised classifiers and unsupervised methods.

## Environment

Your environment is expected to be an Anaconda base environment with Python version 3.6+.

The following needs to be installed to run the code.
- tensorflow
- keras
- plotly
- seaborn
- imblearn
- hmmlearn

## Paper

To contemplate the code, we have written a paper discussing the various methods and techniques used in this project. What approaches we have chosen and why we did certain things and the results we got.
The paper can be found in this github repository as 'DAT550_Report'.