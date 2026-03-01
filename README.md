# A Machine Learning Solution for Predicting the Employees' Promotion Eligibility
The following repository contains the script for Rakamin Data Science batch 61 final project.
To read on how to run the script, please refer to the "Addendum" section.

## Introduction
### Background
Employee promotion refers to the advancement of an employee to a higher position with different responsibilities, status, and usually, greater compensation. Promotion serves as a reward mechanism for (ideally) well-performing employees and for organizations to acquire higher-ranking employees without needing to rely on external sources.

However, the decision to choose the right employees for promotion may be challenging as 82% of managers have admitted to previously promoting the wrong candidates (Gallup, 2014). As 70% of team engagement is attributed to management (Careerminds, 2024), incorrect promotion decision may directly cause low employee morale and increased turnover.

### Problem Statement
Many organizations employ different promotion selection methods. The scope of this essay will only refer to Rakamin’s method where the Human Resource department is in charge of this decision.

Predictably, there are thousand(s) of employees within Rakamin which translates to thousand(s) of rows for the Human Resource department to process. Not to mention that the criteria for promotion might differ between Human Resource personnel.

Moreover, as the decision is made by human personnel, their decision making is also influenced by the quality of data presented to them.

These issues can cause the employee promotion process to be rather lengthy and is prone to the Human Resource officers’ personal biases. As such, this essay will seek to answer the following question: What is the best way to implement a Machine Learning solution that can be applied for the purpose of streamlining this process?

## The Team
### Team Members
This project was done by The Scholars, a group of students enrolling themselves into a Data Science bootcamp organized by Rakamin.
The 4 members of The Scholars are:
- Ryan Karuna (Project Manager/Data Engineer)
- Alya Rahma (Business/Data Analyst)
- Huriya Fajriati (Data Scientist)
- Intan Charolina (Data Scientist)

### Role Description
As the scope of the project is quite large and necessitates a wide-range of skills, members of The Scholars will be divided into the following 4 roles:
- Project Manager:
    - Oversees the project timeline, tasks, and progress of the other team members.
    - Ensuring the overall quality of the project.
- Data Engineer:
    - Handles data cleaning, transformation, and overall data qualities.
    - Perform Exploratory Data Analysis.
- Business/Data Analyst:
    - Define the business problem and metrics.
    - Identifies industry trends and needs.
    - Ensures the overall quality of the presentation visualisation.
- Data Scientist:
    - Experiment with possible applicable Machine Learning models and find the best ones to use on the project.
    - Use various metrics to evaluate the performance of the models tested.
    - Identify issues with the data qualities to improve model performance.

Of note, while every member of The Scholars have their own designated roles, there may be cases where members are required to complete tasks in other roles.

## Methodology
### Exploratory Data Analysis
This is performed to ensure the quality and distribution of the data and is done by observing the numeric attributes of the data, visualizing the columns and using statistical methods to find the correlation and connections between features & labels.

### Data Preprocessing
Since there are null values, invalid values and class imbalance within the dataset. It is required to process the dataset before it can be used to train the Machine Learning models.

### Modeling
The team will attempt to optimize the model by performing Hyperparameter Tuning to improve model performance as well as avoiding overfitting.

## Addendum
To run the script, you have to download preprocessing.py, web_apps.py, kmeans_model.pkl, pca_model.pkl, scaler.pkl, and Rakamin Bootcamp - Dataset - Promotion Dataset.csv. Place the all the files in the same directory. Then, run web_apps.py using the terminal with the following command "streamlit run web_apps.py".

You also need to have a .csv file with the same column names as the dataset to predict the promotion eligibility of employees.