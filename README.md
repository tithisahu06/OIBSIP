# Oasis Infobyte Data Science Internship (OIBSIP)
This repository contains the projects and tasks completed during my one-month Data Science Internship at Oasis Infobyte. The fellowship focuses on gaining a deeper understanding of data science concepts through hands-on application and technical task execution.  

# Project Structure

The repository is organized by tasks, each containing the Jupyter Notebook, dataset, and relevant documentation.

# Internship Details

Organization: Oasis Infobyte  

Role: Data Science Intern  

Duration: 1 Month (April 2026 – May 2026)  

Offer Letter ID: OIB/L2/IP2236

# Task 1: Iris Flower Classification

Objective: To develop a machine learning model capable of classifying Iris species based on their sepal and petal measurements.

Algorithms Used: Implemented Logistic Regression, K-Nearest Neighbors (KNN), and Decision Tree models.

Performance: Achieved a perfect accuracy score of 1.0 across all three models.

Key Insight: The high accuracy is attributed to the Iris dataset being highly linear and well-separated, making it an ideal candidate for these classification algorithms.

Workflow:

Data loading and preprocessing.

Exploratory Data Analysis (EDA) to visualize species distribution.

Model training and comparative performance evaluation.


# Task 2: Unemployment Rate Analysis (COVID-19 Impact)

# Project Overview

This project analyzes the **unemployment rate in India**, with a special focus on the **impact of COVID-19**.
Unemployment rate is defined as the percentage of people in the labor force who are unemployed.

The COVID-19 pandemic caused a significant disruption in employment, making this dataset ideal for data analysis and visualization.

---

# Objectives

* Analyze unemployment trends over time
* Study the impact of COVID-19 on unemployment rate
* Compare unemployment across different regions
* Identify patterns and insights using data visualization

---

# Dataset

* Contains unemployment statistics across different regions in India
* Key features:

  * `Region`
  * `Date`
  * `Estimated Unemployment Rate (%)`
  * `Estimated Employed`
  * `Estimated Labour Participation Rate (%)`
  * `Area`

---

# Technologies Used

* Python 
* Jupyter Notebook 
* Libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn

---

# Data Analysis Steps

1. Data Loading and Exploration
2. Data Cleaning (handling missing values, formatting columns)
3. Time Series Analysis
4. COVID-19 Impact Analysis (Before vs During 2020)
5. Region-wise Unemployment Comparison
6. Correlation Analysis using Heatmap

---

# Key Insights

* A sharp increase in unemployment was observed during **2020 (COVID period)**
* Certain regions were more affected than others
* Gradual recovery trend observed post-lockdown (if applicable)
* Strong relationships exist between employment and labour participation rate

---

# Visualizations

* Unemployment Rate Distribution
* Time Series Trend
* Region-wise Comparison
* Correlation Heatmap

---

# Conclusion

This project highlights how external events like COVID-19 can significantly impact employment trends.
It demonstrates the use of data analysis and visualization techniques to extract meaningful insights.

---


# Task 3: Car Price Prediction using Machine Learning

# Project Overview

Car price prediction is an important application of Machine Learning. The price of a car depends on multiple factors such as brand value, fuel type, mileage, transmission, and more.

In this project, we built machine learning models to predict the selling price of cars based on various features and compared their performance.

# Objective

To analyze car data and identify key factors affecting price

To build and train machine learning models

To compare model performance and select the best one

# Dataset

The dataset contains the following features:

Car Name, Year, Present Price, Kms Driven, Fuel Type, Seller Type, Transmission, Owner, Selling Price (Target Variable)

# Technologies Used

Python 

Jupyter Notebook 

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

# Data Preprocessing

* Checked for missing values

* Converted categorical data using One-Hot Encoding
  
* Removed irrelevant columns
  
* Split data into training and testing sets
  
# Models Used

1. Linear Regression
   
Simple and interpretable model

Assumes linear relationship between features

2. Random Forest Regressor
   
Ensemble learning method

Handles non-linear relationships effectively

# Model Performance Based On RMSE

* Linear Regression->	3.04
  
* Random Forest	—> 0.91

# Result

Random Forest Regressor performed significantly better than Linear Regression

It achieved a much lower RMSE, indicating higher prediction accuracy

# Conclusion

Car price prediction is a regression problem influenced by multiple complex factors

Linear Regression was not able to capture non-linear patterns effectively

Random Forest model provided better results due to its ability to handle complex relationships

Therefore, Random Forest is the best model for this project


# Task 4: Email Spam Detection using Machine Learning

# Project Overview

Spam emails are unwanted messages that often contain advertisements, scams, or phishing content. This project aims to build a machine learning model that can automatically classify emails as Spam or Not Spam (Ham).

# Objective

* To develop an email spam detection system using Python
* To apply Natural Language Processing (NLP) techniques
* To train a machine learning model for accurate classification
  
# Technologies Used

* Python
* Jupyter Notebook
* Pandas, NumPy
* Scikit-learn
* Matplotlib & Seaborn
  
# Dataset

* SMS Spam Collection Dataset
* Contains labeled messages as spam or ham
  
# Project Workflow

* Data Collection
* Data Cleaning & Preprocessing
* Text Vectorization (Bag of Words / TF-IDF)
* Train-Test Split
* Model Training using Naive Bayes
* Model Evaluation
* Testing with Custom Inputs
  
# Model Used

* Multinomial Naive Bayes

# Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
  
# Results

* Achieved high accuracy in detecting spam messages
* Model performs well on unseen data
* Successfully classifies custom email inputs
  
# Key Learnings

* Understanding of NLP techniques
* Text preprocessing and feature extraction
* Implementation of machine learning models
* Model evaluation and performance analysis

# Contact

If you have any questions regarding these projects, feel free to reach out via LinkedIn!
