# ClimateWins_repo
![image](https://github.com/user-attachments/assets/51c47901-2047-4e2e-a04f-d6a5828c935c)


Machine Learning Weather Prediction by ClimateWins 
Python project - optimization towards weather solution and models development on data set.

## Introduction
ClimateWins is a fictitous and non-profit European company dedicated to the project of using technology to predict extreme weather conditions in view of the ever growing global warming phenomenon. It's idea and aims are to be able to predict favourable weather locations for people to relocate to or predict favourable days of week for people to plan their events around. It aims to contribute this value to the inhabitants of continental Europe and ultimately, the world at large.

### Context
I am a data analyst employed by ClimateWins to undergo training in machine learning tools and procedures preparatory to the end results of climate conditions predictions. This project is the first of two legs of my training to acquire adequate knowledge to function in responsibilities that may sometimes involve aspects of data science and engineering along with the main role as an analyst. The entire activity is termed machine learning with python. This first leg involved sourcing a dataset from the European Climate Assessment and Dataset project (ECA&D https://www.ecad.eu/ ). The immediate aim is to use this dataset to predict favourable and unfavourable daily weather conditions in Europe, using supervised machine learning models. The second leg intends to deepen search of models suitable for improvement on the first leg and for predicting specific extreme weather conditions. For real, this is a summary set-up scenario for my data analyst specialization course at CareerFoundry, Berlin, currently ongoing. 

#### Progress Report on Project Phase I
Dataset has been cleaned and profiled for possible limitaions and biases. Study hypotheses were also drawn based on data, variables contained in it and the tools of machine learning. Machine learning optimization has been carried out with Gradient Descent (GD) algorithm in Pythonhe as well. Because of the non-linear relationships in dataset, only classification models of supervised learning would be applicable. Further on this, I have completed classification models using K-nearest neighbour (KNN), Decision Tree (DT) and Artificial Neural Netwrok (ANN) algorithms with varying levels of accuracy for predicting pleasant and unpleasant daily weather. This was just daily instances that is yet to delve into specific weather situations prediction. An interim report has also been prepared in MS PowerPoint for stakeholders at ClimateWins (for real - CareerFoundry). Other reports and Python scripts are atatched in this repository.

##### The Dataset
This dataset from ECA&D is available at this link: (https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv) . The weather dataset consists of records of 8 to 11 weather conditions measurements as variables across each of 18 European weather stations daily and for the time period of 1960 to 2022. Example variables are maximum daily temperature, minimum daily temperature, mean daily temperature, precicipation, wind speed, etc.

###### Data Preparation and Profiling
The dataset was preprocessed: it consisted of no missing values, no duplicates, no inconsistency in naming conventions, and no mixed datatypes. Profiling was done to verify all this in Python. A report of possible limitations was also generated.
