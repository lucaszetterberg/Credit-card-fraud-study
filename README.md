# Credit-card-fraud-study

This study is made as a part of a degree project in the third year of the Computer Science and Engineering Bachelor's programme at the Royal Institute of Technology (KTH) in Stockholm, Sweden. The purpose of the study is to examine two unsupervised clusering algorithms and compare their performance on the "credit card fraud detection" dataset from kaggle.com.

### :inbox_tray: Downloads
These are the resources used in the study outside the python installation. If you do not have them downloaded already, you can easily download them using the command `pip install "package"`.
- os
- Pandas
- Numpy
- Tensorflow (and cuda)
- kagglehub

### :bar_chart: Dataset
As mentioned in the introduction the dataset used is the "Credit Card Fraud Detection" dataset from [kaggle.com](https://www.kaggle.com/). The dataset is imported directly from the `kagglehub` package in python so no manual download is necessary. Although the the dataset is available [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data) for your interest. 

The dataset consists of credit card 284,807 credit card transactions made by European cardholders in September of 2013. Of these 284,807 transactions, 492 were fraudulent rendering the dataset highly unbalanced with a "positive class" consisting of 0.172% of the dataset. 
