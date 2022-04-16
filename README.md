# Data-Cleansing-and-Exploratory-Data-Analysis-of-Titanic-DataSet
The sinking of the Titanic is one of the most infamous shipwrecks in history. In this project the function of Exploratory Data Analysis (EDA) is used to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods.
# Use Case Summary
## Objective Statements
- Get the insight about how many people survived and died
- Knowing the age range and gender of the passengers
- Identify patterns by visualizing data in graphs 
- Discover errors, outliers, and missing values in the data
## Challenges
- Large size of data, can not maintain by excel spreadsheet
- The data have a lot missing values
## Methodology
- Descriptive analysis
- Graph/chart analysis
## Expected Outcome
- Descriptive analysis
= Graph/chart analysis

# Data Understanding
The first step is to understand the dataset we are going to work with. In this Titanic DataSet there where a total of 12 columns. Download the Titanic DataSet: https://bit.ly/TitanicCsvDataSet
- PassengerID	The ID of passengers
- survived	"Survival (0 = No; 1 = Yes)"
- pclass	"Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)"
- name	Name
- sex	Sex
- age	Age
- sibsp	Number of Siblings/Spouses Aboard
- parch	Number of Parents/Children Aboard
- ticket	Ticket Number
- fare	Passenger Fare cabin	Cabin
- embarked	"Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)"

# Data Preparation
Data Preparation is the stage where we prepare tools and materials before carrying out data cleansing and exploratory data analysis.
- Code Used: Python Version 3.10.3
- Packages: Pandas, Numpy, Matplotlib, Seaborn
- IDE: Google Colab

# Data Cleansing
Data cleaning and preparation is an integral part of data science. Oftentimes, raw data comes in a form that isn’t ready for analysis or modeling due to structural characteristics or even the quality of the data. 
1. Import required packages
````
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
````
2. Load Totanoc.csv file
````
from google.colab import files
files.upload()
````
3. Show the loaded dataset
````
df.head()
````
