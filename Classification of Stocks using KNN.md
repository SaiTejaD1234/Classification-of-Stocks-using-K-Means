# **Classification of Stocks using K-Means**

    1. Project Motivation
    2. Objectives
    3. Methods Used
    4. Installation
    5. Data
    6. Implementation
    7. Result

## 1. Project Motivation

Stocks listed in the markets are very numerous and diffuclt to classify using traditional techniques. Hence we need a model which can effortlessly sort our stocks into groups where we can easily choose and pick for our investment portfolio. The stocks tend to behave and exhibit similiar value changes as the markets dynamically vary every second. It is vital to find these stocks which tend to behave similarly to group them into a portfolio. Fortunately a K-Means algorithm is a robust classifier algorithm which classifies our stocks into how "close" they are.

## 2. Objectives

* Obtain the dataset from NYSE and clean it
* Find appropriate features and transform them using MinMax Scaler
* Find the best possible K value using Silhouette Method and group the stocks
* Load the newly generated featured onto the dataset
* Generate the summary of the stock groups and load it into an excel file 

## 3. Methods Used

* Feature Engineering using MinMax Scaler
* Silhouette Method
* K-Means Classifier

## 4. Installation

* Python versions 3.*.
* Python Libraries:
    * Pandas
    * Numpy
    * Sklearn

## 5. Data

The data loaded from the csv file is downloaded from **NYSE**. The dataset has about **750 stocks and 160 features**.

## 6. Implementation

**I've selected 11 features**: *volume, twoHundredDayAverage, shortRatio, enterpriseValue, ebitdaMargins, grossMargins, totalDebt, totalCash, bookValue, trailingEps, and marketCal* for the classification.

A MinMaxScaler has been used to transform the features for faster computing. Silhouette scores has been found out for various K values and has been selected for K-Means algorithm. Clusters have been found and the new feature has been loaded onto the dataset. Further a summary of the groups has also been created.

## 7. Result

A K-Means algorithm has been used to classify stocks. The results are attached in an excel workbook format in the repository.

