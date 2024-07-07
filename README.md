# Chicago Crime Analyzer

This project aims to analyze crime data and build a predictive model to forecast crime rates. The project uses a sample crime dataset and includes steps for data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Table of Contents
- Installation
- Dataset
- Project Steps
  - 1. Data Understanding and Cleaning
  - 2. Exploratory Data Analysis (EDA)
  - 3. Feature Selection and Transformation
  - 4. Model Building
  - 5. Model Evaluation
  - 6. Prediction and Analysis
  

## Installation

pandas
numpy
scikit-learn
matplotlib
seaborn

## Dataset

The dataset used in this project is a sample crime dataset containing information about various crimes, including their types, locations, and dates.

## Project Steps

### 1. Data Understanding and Cleaning

- **Load the dataset** and inspect the columns and data types.
- **Handle missing values** by either dropping rows/columns or imputing values.
- **Convert data types** for columns like dates.

### 2. Exploratory Data Analysis (EDA)

- **Visualize crime counts** per year and per crime type.
- **Plot trends** and identify patterns in the data.

### 3. Feature Selection and Transformation

- **Encode categorical variables** using techniques like one-hot encoding.
- **Select relevant features** for the prediction model.

### 4. Model Building

- **Split the data** into training and testing sets.
- **Train a model** (e.g., RandomForestRegressor) on the training set.

### 5. Model Evaluation

- **Evaluate the model** using metrics like Mean Squared Error (MSE) and R-squared (R²).
- **Make predictions** on the test set and compare with actual values.

### 6. Prediction and Analysis

- **Predict future crime rates** using the trained model.
- **Analyze and interpret** the prediction results.

## PowerBI Visualizations

PowerBI is used to create interactive visualizations and dashboards for the crime data. Follow these steps to create and view the PowerBI reports:

1. **Load the data** into PowerBI.
2. **Create visualizations** such as bar charts, line charts, and maps to explore crime trends and patterns.
3. **Publish the reports** to the PowerBI service for sharing and collaboration.

![Crime_rate_analyser](https://github.com/Santhoshkumar6242/CrimeRateAnalyzer/assets/160504553/d47d4a11-2c83-4fba-990a-90b075d7b26b)

- **Crime Trends Over Years**: A line chart showing the number of crimes per year.
- **Crime Distribution by Type**: A bar chart showing the distribution of different crime types.
- **Geographical Crime Distribution**: A map visualizing the locations of crimes.

