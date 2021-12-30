## Human-or-Bot-ML
To find out if bids from an online auction site belong to a human or bot

## Description

Data is cleaned, extracted and modified before using CatBoostClassifier to predict the outcome

## Getting Started

### Dependencies

* from sklearn.ensemble import RandomForestClassifier
* from sklearn.model_selection import train_test_split
* from sklearn import metrics
* from catboost import Pool, CatBoostClassifier
* import pandas as pd

### Installing

* Place bids / test / train into folder named data
* Rename bids smaller.csv to bids.csv 

### Executing program

* Running the program will produce a my_predictions.csv 

## Version History

* 0.2
    * Changed from RandomForestClassifier to CatboostClassifier as yeilded more accuracy
* 0.1
    * Initial Release

