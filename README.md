# Distributed Data-Analysis and Mining
An academic project carried out for the Distributed Data Analysis and Mining course (a. y. 2022/2023). 

# Methodology

The project was carried out with a local dataset but simulating a distributed scenario using **Apache Spark**. Therefore, I utilized pandas only when I needed to display a variety of short dataframes or series, such as summary tables, and I used **PySpark** in a distributed fashion in all other situations.

# Project tasks

* Pre-processing:
  Apply one or more imbalanced techniques to the fraud_bool variable. Apply the one hot encoding transformation on the nominal variables. Perform a feature selection analysis.
* Clustering:
  Identify different groups of clients and characterize the clusters according to the probability of fraud.
* Classification:
  Perform a binary classification on the target variable fraud_bool using different classifiers. Moreover, perform a supervised analysis within each cluster and see how this affects the quality of the predictions.
  
# About the dataset

The Bank Account Fraud (BAF) is a suite of six artificial datasets related to bank account opening applications. The datasets were created by Jesus et al. [@2022](10.48550/ARXIV.2211.13358) and published at
NeurIPS 2022. The project was funded by Feedzai. The csv files are available at the following link on [@Kaggle](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022). 

Each dataset is composed of synthetic instances generated using a CTGA, a collection of deep learning based synthetic data generators, which can learn from real data and generate synthetic records with
high fidelity. The analyses was conducted on the Base.csv dataset, since it is the one most similar to the original data used to train the generator. The size of the dataset is 216.59 MB. It is composed of 1 000 000
records and 32 columns, both qualitative and quantitative.
