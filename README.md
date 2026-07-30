# machine_learning_project
This is a machine learning project for MSDS.

🚴 Bike Rental Data Analysis with Pandas
Overview

This repository contains my solution for the MDS 640 – Machine Learning: Pandas Review Assignment. The project demonstrates fundamental data manipulation techniques using Python, Pandas, and NumPy to prepare a real-world dataset for machine learning and data analysis.

Data preparation is a critical step in the data science workflow, often representing the majority of the effort before modeling begins. This assignment focuses on cleaning, combining, transforming, and organizing data into a final analytical dataset.

Objectives

The notebook demonstrates how to:

Import and work with multiple datasets
Handle missing values
Concatenate DataFrames
Merge datasets using multiple keys
Create new calculated features
Remove unnecessary columns
Rename columns for readability
Reorder columns into a logical structure
Sort and reset DataFrame indexes
Prepare a clean dataset for future machine learning tasks
Dataset

The project uses hourly bike rental data combined with weather information from two separate years.

The data includes information such as:

Date and time
Season
Temperature
Humidity
Wind speed
Weather conditions
Casual rentals
Registered rentals
Hourly bike rental counts
Technologies Used
Python 3
Pandas
NumPy
Jupyter Notebook
Data Preparation Workflow

The notebook performs the following steps:

Import required libraries
Load bike rental and weather datasets
Fill missing temperature values for February 2012
Combine the 2011 and 2012 bike rental datasets
Merge bike rental data with weather data
Create a total_count feature by combining casual and registered rentals
Remove redundant columns
Rename columns for improved readability
Reorder columns into a consistent structure
Sort the dataset chronologically
Reset the DataFrame index
Produce a final cleaned dataset (bike_final)
Skills Demonstrated
Data Cleaning
Data Wrangling
Feature Engineering
Missing Value Treatment
DataFrame Merging
DataFrame Concatenation
Column Transformation
Data Preparation for Machine Learning
Exploratory Data Preparation
Pandas Best Practices
Repository Contents
.
├── Bennett_pandas_assignment.ipynb
├── bike_per_hour_2011.csv
├── bike_per_hour_2012.csv
├── weather_2011_2012.csv
└── README.md
Learning Outcomes

Through this assignment, I strengthened my ability to prepare structured datasets for machine learning by applying core Pandas operations used in real-world data science projects. The notebook demonstrates clean, organized, and reproducible data preprocessing techniques that form the foundation of predictive analytics workflows.

About Me

Shalaunda Bennett

Software Engineer | Data Science Graduate Student | Business Analyst

I have over 20 years of experience in technology and am currently completing a Master of Science in Data Science. My interests include machine learning, data analytics, business intelligence, and using data to solve complex business problems.

License

This repository was created for educational purposes as part of coursework in the MDS 640 Machine Learning program.
