# -Diabetes-data-science-project

Python, Machine learning, EDA, Data cleaning

Introduction: This is a data science analysis project that aims to predict diabetes based on various health-related features. The dataset used in this project contains information about individuals, including their age, gender, BMI (Body Mass Index), HbA1c level (a measure of blood glucose, blood glucose level, hypertension status, heart disease status, and smoking history. The goal of the project is to build and compare machine learning models to accurately predict whether an individual has diabetes or not.

Project Overview: 
1. Data Import and Exploration: 
The project begins by importing necessary libraries for data analysis and visualization.
 The dataset is read from a CSV file and its dimensions are checked. 
2. Data Preprocessing: 
   - Data types of specific columns are converted to appropriate types. 
   - Missing values in each column are identified and handled. 
3. EDA: Data Visualization: 
   - Visualizations are created to understand the distribution of different variables. 
   - Gender distribution is visualized using a pie chart and a bar plot. 
   - Numerical variables are visualized using histograms with KDEs and box plots. 
   - Correlation between numerical variables is visualized using a pair plot and a heatmap. 
4. Data Cleaning: 
   - Outliers are detected and removed from numerical columns using a custom function. 
   - The DataFrame is reset to a new sequential index. 
5. Data Splitting: 
   - The data is split into feature variables (X) and the target variable (y). 
   - Feature scaling is applied to the feature variables. 
   - The data is further split into training and testing datasets. 
6. Model Building and Evaluation: 
   - Four machine learning models are built and evaluated using different evaluation metrics. 
   - The models used are: Logistic Regression, Decision Tree, Random Forest, and K Nearest Neighbors (KNN). 
   - Evaluation metrics include accuracy, classification report, confusion matrix, mean squared error, and R2 score. 
7. Model Comparison: 
   - The accuracy scores of all models are displayed in a table for easy comparison. 
   - The Decision Tree model performs the best with an accuracy of almost 97.4%. 

Conclusion: 
This project provides a comprehensive analysis of the diabetes prediction dataset using data visualization and machine learning techniques. By comparing multiple models, the Decision Tree model is identified as the most accurate in predicting diabetes based on the given features. The project serves as a valuable resource for understanding the predictive power of different machine learning algorithms in healthcare-related applications. 
