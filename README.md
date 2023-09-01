# wine-quality-prediction

## 1. Dataset Overview

### Introduction
These datasets are related to red variants of the Portuguese "Vinho Verde" wine. The dataset describes the amount of various chemicals present in wine and their effect on its quality. The datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Our task is to predict the quality of wine using the given data.

These datasets are from one of the many competitions from [Kaggle](https://www.kaggle.com/competitions/wine-quality-pred/overview) and the scoring metric for this competition is categorization accuracy. We were given two datasets, a training, and a testing dataset, both of which were CSV files. The train dataset comprised similar columns to the test dataset, however, had a quality column that differentiated it from the test dataset.

### Description
Input variables (based on physicochemical tests):
1 - Fixed acidity
2 - Volatile acidity
3 - Citric acid
4 - Residual sugar
5 - Chlorides
6 - Free sulfur dioxide
7 - Total sulfur dioxide
8 - Density
9 - pH
10 - Sulphates
11 - Alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10)

### Project Goal/Motivation
One of the goals of this project is to construct a prediction model that infers wine quality based on some chemical facts. We also intend to find the most important factors that drive how good or bad a wine can be. 

## 2. Data Collection and Exploration
Data was downloaded from the Kaggle competition website using my unique Kaggle API key. See the steps below.

(wine_pred1.PNG)

The train dataset was checked for missing info and duplicates.

(wine_pred2.PNG)


## Exploration data analysis



