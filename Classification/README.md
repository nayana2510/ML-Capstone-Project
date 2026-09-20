# REVIEW 1 – Machine Learning Project

## RT-IoT2022 Network Traffic Classification

### Project Overview

This project focuses on applying machine learning techniques to classify network traffic using the **RT-IoT2022 dataset**. The dataset contains network traffic information collected from IoT environments, including both normal and attack traffic.

The main objective of this project is to explore the dataset, preprocess the data, perform feature engineering, and build classification models that can identify the type of network traffic based on its characteristics.

### Dataset

The **RT-IoT2022 dataset** is obtained from the UCI Machine Learning Repository.

**Dataset:** RT-IoT2022
**Task:** Multi-class Classification
**Target Variable:** `Attack_type`
**Number of Instances:** 123,117
**Domain:** IoT Network Security / Intrusion Detection

**Dataset Source:**
https://archive.ics.uci.edu/dataset/942/rt-iot2022

### Project Workflow

The project is divided into the following stages:

1. **Exploratory Data Analysis**

   * Understanding the dataset structure
   * Checking data types and dataset dimensions
   * Checking missing values and duplicate records
   * Studying the distribution of attack classes
   * Analysing numerical and categorical features
   * Visualising correlations and feature relationships
   * Inspecting outliers

2. **Data Preprocessing and Feature Engineering**

   * Removing unnecessary index columns
   * Removing constant features
   * Checking infinite values
   * Handling potential outliers using IQR-based capping
   * Splitting the dataset into training and testing sets
   * Encoding categorical features using One-Hot Encoding
   * Scaling numerical features using StandardScaler
   * Creating additional network traffic features

3. **Classification Model Development**

   Five classification algorithms are implemented:

   * Logistic Regression
   * Decision Tree Classifier
   * Random Forest Classifier
   * K-Nearest Neighbors (KNN)
   * Gaussian Naive Bayes

4. **Model Evaluation**

   The classification models are evaluated using:

   * Accuracy
   * Weighted F1-score
   * Confusion Matrix

   The results are compared to understand how the different models perform on the multi-class network traffic classification task.

### Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Project Structure

```text
Machine-Learning-Project/
│
├── RT_IoT2022.CSV
├── RT_IoT2022_Classification.ipynb
└── README.md
```

### Expected Outcome

The project demonstrates the complete machine learning workflow, starting from exploratory data analysis and preprocessing to classification model training and evaluation.

The final results provide a comparison of multiple machine learning approaches for classifying different types of IoT network traffic using the RT-IoT2022 dataset.

### Dataset Reference

Sharmila, B. S. and Rohini Nagapadma.
**RT-IoT2022.** UCI Machine Learning Repository, 2023.


