# Predicting stock return with Twitter tweets in R 
Data from kaggle : https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020

## Idea 
The initial idea is to simplified the returns to binary outcomes : 1 for positive return and 0 otherwise. 
The concept is to try and predict the daily return. 

### FAANG companies 
Since FAANG has a huge weight on the market (S&P 500) 

## Pre-processing
1. Replacing HTML 
2. Replacing URL 
3. Replacing Emoji 
4. Removing missing values
5. Created binary indicator (made_money) based on stock return
6. Generated DFM to identify common bigrams and unigrams, excluding company names using a custom stop list to avoid bias

## 

## Models 
1. N-gram LASSO 
