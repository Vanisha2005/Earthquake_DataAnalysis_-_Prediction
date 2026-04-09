# Earthquake_DataAnalysis_-_Prediction
Earthquake Data Analysis and Prediction project using Python. Includes data cleaning, feature engineering, exploratory data analysis, and visualization. A Linear Regression model is applied to study patterns and understand relationships in seismic data.

## Earthquake Data Analysis and Prediction using EDA & Machine Learning
Overview
This project focuses on analyzing global earthquake data using Exploratory Data Analysis (EDA) and applying a Linear Regression model to understand patterns in earthquake magnitude. The goal is to extract meaningful insights from seismic data and study relationships between key features.

# Problem Statement
Earthquakes are complex natural events influenced by multiple geological factors. Predicting their magnitude using limited surface-level features is challenging. This project aims to analyze earthquake data and evaluate how well machine learning can model such patterns.

# Objectives
Perform data cleaning and preprocessing
Handle missing values using statistical methods
Conduct exploratory data analysis to identify patterns
Create meaningful features from time data
Build a Linear Regression model
Evaluate model performance using standard metrics

# Dataset
The dataset contains global earthquake records with features such as magnitude, depth, latitude, longitude, and time.
Time Range: 2000 – 2026
Source: Public earthquake dataset

# Project Structure
├── data/
│   └── earthquake_2004_2026.csv
├── notebooks/
│   └── earthquake_analysis.ipynb
├── outputs/
│   ├── magnitude_distribution.png
│   ├── depth_vs_magnitude.png
│   ├── yearly_trend.png
│   ├── correlation_heatmap.png
│   └── ...
├── requirements.txt
└── README.md

# Methodology
1. Data Preprocessing
Converted time column to datetime format
Removed invalid entries
Handled missing values using mean and median
Removed duplicate records

2. Exploratory Data Analysis
Distribution analysis of earthquake magnitude
Outlier detection using boxplots
Trend analysis over years
Geographical visualization of earthquake locations
Correlation analysis between features

3. Feature Engineering
Extracted year and month from time
Created magnitude categories using binning
Prepared data for modeling

4. Model Building
The following model was implemented:
Linear Regression: Works as a baseline model but struggles due to weak linear relationships in seismic data

6. Model Evaluation
Model performance was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

# Visual Analysis
Magnitude Distribution
Shows how earthquake magnitudes are distributed across categories

Correlation Heatmap
Highlights relationships between numerical features

Yearly Trend
Displays variation in earthquake frequency over time

Geographical Distribution
Shows clustering of earthquakes across different regions

# Key Insights
Most earthquakes fall in the low to moderate magnitude range
A significant number occur at shallow depths
Weak correlation exists between depth and magnitude
Earthquake occurrences vary across time and location

# Run the notebook
http://localhost:8888/lab/tree/OneDrive/Desktop/INT375/Earthquakeanalysisml.ipynb

# Requirements
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn

# Results and Insights
This project demonstrates how EDA helps uncover meaningful patterns in real-world datasets. It also highlights the limitations of Linear Regression when dealing with complex, non-linear natural phenomena like earthquakes.

# Future Work
Apply non-linear models (Decision Tree, Random Forest)
Include more geological features
Build a more accurate predictive system
