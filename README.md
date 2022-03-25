# MachineLearningOne
#### Ricco Ferraro, David Grijalva, Nicole Norelli, & Mingyang Nick Yu

## Project Overview

LendingClub, a peer-to-peer lending company where individuals can apply for loans and investors can elect to commit money. The dataset we downloaded was from Kaggle. It contains 2,925,493 records and 141 attributes collected between 2007 and 2020 and was available to the public through LendingClub. The original purpose of the data collected was for LendingClub to accept or reject a loan application as well as assign the loan a grade and interest rate. This is a valuable dataset because each entry has extensive information about the borrower, loan terms, and loan outcome. See dataset at link below:

https://www.kaggle.com/ethon0426/lending-club-20072020q1

Several labs were created around this dataset, with lab one focusing on initial exploration of the dataset, included handling Missing Data, Data Imputation, Creating New Features, Simple Statistics analysis, Visualization of attributes both individually and jointly as well as dimension reduction techniques such as PCA. Mini Lab and Lab Two focused on building machine learning pipeline and using various machine learning techniques to predict a loan default prior to occurrence or predicting loan grade prior to application. Methods used in these two labs including SVM, Decision Tree, Logistic Regression, Random Forest, XGBoost, Deep Neural Network. Grid Search and Stratified Cross validation is utilized for testing each method, and validation set was use to compare performance between models. Lab Three is focused on using different Clustering techniques as preprocessing step to potentially further boosting performance for prediction. Methods used including KMeans, Birch, Spectral Clustering and Gaussian Mixtures. Custom Transformers were created in order to utilize some clustering technique that didn't came with fit, transform or predict function such as Spectral Clustering. Individual class including its own fit, transform and utilizing KNNClassifier for prediction is demonstrated. 

Please see details in each individual notebook in this repository.


## Installing Virtual Environment

### Prerequisites
- Ensure Python 3.9 is installed in your machine  
### Instructions

- Clone this repo in the desired directory
- `cd` to the directory where you wish to save the env. To ensure that we don't accidentally upload the env to GitHub I recommend not creating the env in the same directory you cloned this git repo and having a separate directory exclusively for the env. 
- Use the following command to create the env using Python 3.9 `Python3.9 -m venv <NameOfEnvironment>`
- Go to the directory of the newly created env `cd <NameOfEnvironment>` 
- Activate the environment using the following command  `source bin/activate`. To verify the env is activated check if the name of the env is in front of the terminal prompt. `(<NameOfEnvironment>)`
- To verify your env is using Python 3.9 used `python -V`
- `cd` back to the directory containing the `requirements.txt` file and `pip install -r requirements.txt` 
- Use `pip freeze` to ensure all packages are properly installed 
### Libraries installed
- `scikit-learn==0.24.1`
- `jupyterlab==3.0.14`
- `scipy==1.6.2`
- `numpy==1.20.2`
- `pandas==1.2.4`
- Other libraries that are dependancies to the ones mentioned above 
- Different packages are utilized with different labs, and they are listed at the beginning of each notebook

