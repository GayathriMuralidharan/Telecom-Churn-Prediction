# Telecom Customer Churn Prediction

## Project Overview
This project aims to address the problem of predicting customer churn in the telecom industry. The workflow follows a structured approach, including data analysis, model building, and evaluation to find the best predictive model. By using key metrics, this project helps telecom companies mitigate customer churn and gain valuable insights.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - Seaborn
  - Plotly
  - Scikit-learn
  - Matplotlib

## Dataset
The dataset used in this project contains information about telecom customers, including their usage patterns, subscription details, and whether they churned (left the service) or not. 

## Project Workflow

### 1. Data Collection
The project begins by importing necessary libraries and loading the dataset for analysis.

### 2. Exploratory Data Analysis (EDA)
Exploratory Data Analysis is conducted to explore the dataset's characteristics, identify trends, and uncover potential relationships between features.

### 3. Data Visualization
Interactive data visualization techniques are used to enhance understanding of key data patterns and trends using Seaborn and Plotly.

### 4. Model Building
Five distinct machine learning models are trained to predict customer churn:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- K-Nearest Neighbor (KNN)
- Naive Bayes Classifier

### 5. Model Evaluation
The models' performances are evaluated using metrics like:
- AUC (Area Under the Curve) Scores
- ROC (Receiver Operating Characteristic) Curves

These metrics help in comparing the models and selecting the most effective one for prediction.

## Results
- The model comparison based on AUC and ROC scores shows which model performs the best in predicting telecom customer churn.

## Conclusion
This project successfully develops a reliable predictive model for customer churn, which can help telecom companies improve customer retention and reduce churn rates by offering targeted interventions.
