# Understanding AirBnB prices in Seattle
## Table of Content

 1. Libraries used
 2. Background
 3. Project motivation
 4. File description
 5. Summary of the results
 6. Other
_______
### Libraries used
- python
- Pyspark
- pandas
- numpy
- datetime
_______

### Background
As one of many problems Data Scientists face in business, predicting churn rates is a common problem  amongst them that data scientists regularly encounter. As customer acquisition costs are typically high, it is crucial for companies to identify customers that are likely to church and take action beforehand. Therefore, the goal is to provide insides into behavior of users that church and users that do not as well as to predict churned users based on activities and attributes data of them.

_______

### Project Motivation

The project ist udacity's capstone project for the data science nano degree, using spark to analyze user behavior data from music app Sparkify. By working on the project participants are urged to develop the following skills:

- Loading large datasets into Spark and manipulating them using Spark SQL and Spark Dataframes
- Using the machine learning to build and tune models
- Integrate the skills in the Spark course and the Data Scientist Nanodegree

_______
### File description

Sparkify.ipynb is the main file for the project, it demonstrates the process of using pyspark to explore the data and build the model. The HTML version is just a backup if there are any issues with the ipynb file.
_______
### Summary of results

I modelled three different classification algorithms:
- Logistic regression
- Random forest
- Support Vector machines

In order to determine their performance, I chose the F1 score, since the labeled data is imbalanced (way more users that did not churn compared to the ones that churn. Based on the F1 score, Log regression and SVM perform best, however, it is a very small dataset for both, validation and training so that the next step would be to run the modelling on a bigger dataset.
___
### Other

If you are even more interested, I am outlining my results in a blogpost. If you are interested, check it out and please feel free to get in touch: 
