# Predict-Feature-Sales

## Data Description
You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

## File Descriptions
sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.
test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.
sample_submission.csv - a sample submission file in the correct format.
items.csv - supplemental information about the items/products.
item_categories.csv - supplemental information about the items categories.
shops.csv- supplemental information about the shops.

Accesing the data: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview

## Data Fiels
ID - an Id that represents a (Shop, Item) tuple within the test set
shop_id - unique identifier of a shop
item_id - unique identifier of a product
item_category_id - unique identifier of item category
item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
item_price - current price of an item
date - date in format dd/mm/yyyy
date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
item_name - name of item
shop_name - name of shop
item_category_name - name of item category
This dataset is permitted to be used for any purpose, including commercial use.

## Project Tasks
1. Introduction

2. Importing libraries

3. Importing Dataset & Data Overview

4. Understanding the Dataset & Data Cleaning

    4.1 Train Set Distribution
    
    4.2 Checking
    
    4.3 Delete Data Duplicated
    
    4.4 Check Qutliers
    
    4.5 Checking Train & Test Set

5. Seasonality

6. Exploratory Data Analysis (EDA)

    6.1 Russian Holidays & Observances
    
7. Feature Engineering

    7.1 Lagged Features
    
    7.2 Features of Columns
    
8. Models

    8.1 Light GBM
    
    8.2 XGBoost
    
    8.3 Sequential
