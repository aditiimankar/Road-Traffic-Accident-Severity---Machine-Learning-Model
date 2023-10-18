
# Classification-  Road Traffic Accident Severity
This is a multiclass classification project to classify the severity of road accidents.This project is based on real-world data and the dataset is also highly imbalanced
The degree of severity in road traffic accidents hinges on a multitude of factors encompassing the characteristics of the involved vehicles, drivers, casualties, and the prevailing environmental conditions. The primary objective of this project is to construct predictive models that leverage these factors to categorize accident severity into three classes: minor injury, significant injury, or fatal injury. The dataset employed for this project was curated from manual records of road traffic incidents spanning the years 2017 to 2020, sourced from the police departments within Addis Ababa sub-city. The data encoding process has been undertaken with utmost care to exclude any sensitive information. The final dataset comprises records for 12,316 accidents, each featuring 32 distinct attributes.

#Problem Statement: 
The target feature is Accident severity which is a multi-class variable. The task is to classify this variable based on the other 31 features step-by-step by going through each day's task. Your metric for evaluation will be f1-score.

#Tasks and techniques used:
1. Exploratory data analysis using matplotlib and seaborn

2. Data preparation and pre-processing: 

-Missing Values Treatment using fillna method

-Encoding using pandas get dummies

-Feature selection using chi2 statistic and SelectKBest method

-Imbalance data treatment using SMOTENC technique

3. Modelling using sci-kit learn library:

-Baseline model using RandomForest using default technique

-Tuned hyperparameters using n_estimators and max_depth parameters

4. Evaluation:

-Evaluation metric was weighted f1_score

-Baseline model evaluation fl_score = 81%

     
