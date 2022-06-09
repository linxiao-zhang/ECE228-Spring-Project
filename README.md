# A recommender system

## Team Members
* LinXiao Zhang
* JiaXuan Zhang
* YuQing Shen

## Objective
  As the pandemic continues, people tend to spend more time shopping on E-commerce platforms rather than shopping in real life. Under this background, it is increasingly important for E-commerce platforms to accurately analyze the likes and dislikes of each user, and recommend merchandise that the users need the most. In this project, our team utilizes XGBoost and DeepFM to build a recommendation system that gives accurate suggestions for most of the users. We expect our model to have relatively good metric values in Precision, Recall and F1 score. 

## File Structure

```
|-- ROOT
  |-- README.md
  |-- data
  |-- DeepFM.py
  |-- DataOverview.py
  |-- DataCleaning.ipynb
  |-- Train.ipynb

```
## Dataset

The dataset link is https://drive.google.com/drive/u/0/folders/17R0kYX5USR7cAkyPFXG5KumDUNV9bCzE?ths=true, there are two csv files, you can download them and put them into folder data

## Data Overview

run DataOverview.ipynb to get an overview of the dataset

## Dataset Preprocessing

run DataPreprocess.ipynb to preprocess the data and generate five csv files in the folder data. The five csv files are data_eval.csv, data_test.csv, data_train.csv, item_data.csv, user_data.csv  

## Run the code
run Train.ipynb to get the result


