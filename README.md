# Fraud-Detection-in-Health-Care-Charges

This repository contains Python code for detecting healthcare fraud using machine learning techniques such as PCA and KNN classification.

# Table of Contents
1. Problem Description
2. Data preprocessing
3. Feature Engineering
4. Dependencies
5. Usage

# Problem Description
The objective of this project is to apply unsupervised machine learning techniques, specifically PCA and KNN, to identify unusual data points in a dataset. By comparing and analyzing the results from these algorithms, we aim to assess their effectiveness in detecting outliers and gain insights into exceptional data patterns for potential business implications.

The code in this repository addresses the problem of healthcare fraud detection using machine learning algorithms. It performs the following tasks:

# Data preprocessing:

1. Loading the dataset (inpatientCharges.csv).
2. Handling missing values by filling them with the mean.
3. Removing duplicate records.
4. Converting columns with '$' to numeric values.
5. Identifying and handling outliers using z-scores.
6. Creating new features based on domain knowledge.

# Feature engineering:

Calculating proportions, ratios, squares, logs, and other transformations to create meaningful features for fraud detection.
# Dimensionality reduction:

Applying PCA (Principal Component Analysis) to reduce the dimensionality of the dataset while preserving important information.
# Fraud detection using KNN:

1. Splitting the data into training and testing sets.
2. Scaling the features using StandardScaler.
3. Training a KNN (K-Nearest Neighbors) classifier to detect fraudulent cases.
4. Evaluating the model using accuracy, precision, recall, and F1-score metrics.
# Dependencies
The code relies on the following libraries:

1. pandas
2. numpy
3. matplotlib
4. seaborn
5. sklearn
6. pyod
7. You can install these dependencies using the following command:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn pyod
# Usage
Clone the repository to your local machine.
Install the dependencies as mentioned above.
Ensure you have the inpatientCharges.csv dataset in the same directory as the Python script.
Run the Python script (Fraud_Detection.py) to execute the fraud detection pipeline.
Check the output for PCA results and model evaluation metrics.
