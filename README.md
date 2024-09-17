**##ECE 2112: ADVANCED COMPUTER PROGRAMMING AND ALGORITHMS**

**EXPERIMENT 3**

**PYTHON DATA ANALYSIS (PANDAS)**

Pascual, Jasmine Nicole S.

2ECE-B

September 17, 2024

**I. Intended Learning Outcomes:**

1. To identify the codes and functions incorporated in the Pandas library
2. To be able to apply and use the different codes and functions in creating a Python program using a Pandas library

**II. Instructions:**

Write a Python script/code in the Jupyter Notebook to do the given problems. 
You may submit your Jupyter notebook in the dedicated submission bin.

For this programming assignment. download the following file and save to your default user folder:
http://bit.ly/Cars_file
##
**PROBLEM 1**
Save your file as Surname_Pandas-P1.py

Using knowledge obtained from the experiment and demonstrations:

a. Load the corresponding .csv file into a data frame named cars using pandas

b. Display the first five and last five rows of the resulting cars.

**Python code:**

import pandas as pd _#Access the Pandas library_ 

cars = pd.read_csv('cars.csv') _#Load the .csv file into a DataFrame called 'cars'_

cars _#Display the DataFrame 'cars'_

print("First five rows of the resulting cars:") _#Present a statement introducing the first 5 rows of the DataFrame_ 

print(cars.head()) _#Display the first 5 rows of the DataFrame 'cars'_

print("Last five rows of the resulting cars:") _#Present a statement introducing the last 5 rows of the DataFrame_

print(cars.tail()) _#Display the last 5 rows of the DataFrame 'cars'_

##

**Progress Tracker:**

Semptember 17, 2024: Created the repository, created the Python program for Problem 1, and submitted through Canvas.
