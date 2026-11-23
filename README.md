# Medical_Insurance_cost_Prediction
Project Overview
This project focuses on exploring the factors that influence individual medical insurance charges and developing a machine learning model to predict insurance costs based on an individual's characteristics.
Using Python and machine learning techniques, the project examines patterns in healthcare expenses, identifies the factors that contribute most to insurance charges, and compares the predictive performance of different regression models.
Problem Statement
Insurance companies need reliable ways to estimate the medical expenses of their customers to support effective pricing, risk assessment, and financial planning.
The goal of this project is to build a predictive model that estimates individual medical insurance charges using relevant demographic and lifestyle information.
Project Objectives
•	Explore the medical insurance dataset and understand its structure.
•	Investigate how age, BMI, smoking habits, number of children, sex, and region influence medical insurance charges.
•	Compare the average insurance charges of smokers and non-smokers.
•	Perform exploratory data analysis (EDA) to identify patterns and relationships.
•	Develop regression models to predict medical insurance costs.
•	Compare Linear Regression and Random Forest Regression models.
•	Identify the most influential factors affecting insurance charges.
•	Provide insights that can support insurance pricing and risk assessment.
Dataset
The dataset used for this project is the Medical Cost Personal Dataset, obtained from Kaggle.
Source: Medical Cost Personal Dataset – Kaggle
The dataset contains the following variables:
Column	Description
age	Age of the individual
sex	Gender of the individual
bmi	Body Mass Index
children	Number of dependants
smoker	Smoking status (yes/no)
region	Residential region
charges	Individual medical insurance charges
The target variable for prediction is charges.
Tools 
The following tools and libraries are used:
•	Python: Main programming language.
•	Pandas: Data manipulation and analysis.
•	NumPy: Numerical computations.
•	Matplotlib: Data visualization.
•	Seaborn: Statistical data visualization.
•	Scikit-learn: Machine learning and model evaluation.
•	Jupyter Notebook: Data analysis and model development.
Project Workflow
1. Data Loading and Inspection
•	Import the dataset using Pandas.
•	Examine the dataset structure, dimensions, and data types.
•	Check for missing values and duplicate records.
•	Understand the distribution of the variables.
2. Exploratory Data Analysis (EDA)
•	Analyze the distribution of medical insurance charges.
•	Compare average charges between smokers and non-smokers.
•	Examine the relationship between age and insurance charges.
•	Investigate how BMI, children, sex, and region relate to insurance costs.
•	Use visualizations to identify important patterns and trends.
3. Data Preprocessing
•	Prepare the dataset for machine learning.
•	Encode categorical variables.
•	Separate the independent variables (features) from the target variable.
•	Split the dataset into training and testing sets.
4. Model Development
Two regression algorithms are explored:
•	Linear Regression: Used as a baseline model to understand the linear relationship between customer characteristics and insurance charges.
•	Random Forest Regression: Used to capture more complex relationships and interactions between the features.
5. Model Evaluation
Evaluate and compare both models using appropriate regression metrics:
•	Mean Absolute Error (MAE).
•	Mean Squared Error (MSE).
•	Root Mean Squared Error (RMSE).
•	R-squared (R²).
6. Insights and Recommendations
Identify the factors that contribute most to medical insurance charges and provide recommendations for insurance pricing and risk assessment.
Project Structure
The repository will contain:
README.md: Project Description and Documentation
Medical_Insurance_cost_Prediction.jpynb: Data Analysis and Learning Notebook
Requirement.txt: Python Libraries
Group Members
1. Nwine Confidence Abednego
2. Nnanyere Success Ihechukwu
3. Adesope Rofiah Olajumoke
4. Igwe Esther chinasaram
5. ⁠Ibiyemi Raab Temitope
6. ⁠Agbowo Samiah Motunrayo
7. Raphael Ugwu
8. Salaudeen Rokeeb oyetunji
9. Sewo Rachael Olajumoke
10. ⁠Lawal Samuel Temidayo
11. Ukwuani Emmanuel Izuchukwu
12.  Awoyemi Promise Adedotun
