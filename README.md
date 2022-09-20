# Regression - ML

## 1.1 PROJECT SCOPE

The goal of the research is to forecast airline ticket prices using historic data.
Regression from a machine learning model is used in several steps to make predictions.
Data pre-processing, analysis, EDA, bivariate analysis, encoding, splitting the data, data visualization, model creation, and other processes are used to achieve this.

Here, in addition to using Cufflinks and Plotly to encode data and segregate it by categorical and numerical data, we additionally retrieve data by day, month, and year.
To identify the optimum techniques for calculating the score, we have additionally automated the ML pipeline and fine-tuned the ML model.



## 1.2 BRIEF DISCUSSION

Importing the dataset's necessary libraries and outlook for better comprehension.


### Data pre-processing

At a vital point in the data processing process, we replace missing values.
The Duration column is a pre-process to help the ML model be understood better.

### Feature Engineering

We fetch the column here by day, month, and year. We additionally embellish it and polish the columns.

### Analysis

We determine when the majority of flights will depart.
The study reveals that early morning is the time when most flights will depart.
For the purpose of making it simple to interpret the analyzed data, we utilize Cufflinks & Plotly.
Here, it is very obvious that the price of a flight rises as the number of minutes grows. After discovering that Cochin is the bulk of flights' final destination

### Exploratory Data Analysis (EDA)

Here, we employ bivariate analysis to generate some business knowledge.
With the exception of the airline, we have determined that Jet Airways Business has the highest pricing.

### Encoding

Here, we use One-hot to process the data and eliminate certain unnecessary features. We removed any extra columns.

Data that have the data-type "object" are categorical in nature. Data with a data type of int or float are considered numerical data.

Performing target guided mean encoding and discovering that Greater Noida (Jewar), which will house Delhi's second airport, is still under construction.

MANUALLY ENCODE THE "Total stops" column. Also carry out outlier detection.

### Machine Learning Model

To define a basic random forest model, we divided the dataset into train and test groups.
Later on, we'll try to use some parameters to improve this model.
The ML model being saved to disc. Establishing custom assessment metrics.

### Automate Machine Learning Pipeline

Here, we automate the model through training, testing, and scoring using an algorithm.
We "Hyper parameter Tuning or Hyper parameter Optimization," create search & apply search on Training data or Fit the CV model, and Check the best parameters and best score.



## 1.3 PROJECT GOAL

The project's objective is to forecast the cost of airline tickets while utilising machine learning to determine the optimum score.
We can determine the cost of an aeroplane ticket through the method.
Most airlines' destinations, according to our research, are Cochin, Bangalore, Delhi, etc. Additionally, fewer flights take off in the middle of the night than in the morning.

The project's insight allows us to see plainly that flight prices rise as minute length grows.
The correct model is used to make the prediction, and it is saved on disc for later use.
The ML workflow has also been automated, and the ML model has been hyper tuned.
