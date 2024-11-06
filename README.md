## Predicting Diabetes Using Machine Learning
Table of Contents
Introduction
Background
Problem Statement
Project Objectives
Data Description
Insights and SQL Analysis
Data Preprocessing
Algorithms Used
Performance Measurement
Results and Comparison
Discussion
Conclusion
References

## Introduction
Diabetes is one of the fastest-growing global health challenges, affecting over 400 million people worldwide. The disease results from factors such as obesity, inactivity, and poor diet, and can lead to serious complications like vision loss, stroke, and kidney failure. This project aims to leverage machine learning algorithms to predict diabetes accurately, enabling early detection and prevention.

## Background
Diabetes is classified into three types:
Type 1: Often diagnosed in children and young adults; an autoimmune disorder.
Type 2: A chronic condition mainly affecting middle-aged and older adults, though increasingly observed in children due to obesity.
Gestational Diabetes: Occurs during pregnancy, potentially leading to Type 2 diabetes later in life.
The growing prevalence of diabetes, especially in developing countries, emphasizes the need for predictive tools to aid in early diagnosis and management.

## Problem Statement
Diabetes diagnosis can be complex due to the variation in symptoms across patients. Identifying patients with diabetes using specific health metrics like blood glucose levels, blood pressure, and BMI can improve early detection and enable proactive healthcare interventions.

## Project Objectives
The objective of this project is to build predictive models using machine learning to classify whether individuals have diabetes. Various algorithms, such as Decision Trees, Artificial Neural Networks (ANN), and Gradient Boosting, are applied to compare performance and determine the most effective approach.

## Data Description
The dataset, sourced from the Pima Indians Diabetes Database on Kaggle, contains information on female patients of Pima Indian heritage. Key attributes include:

Pregnancies: Number of pregnancies
Glucose: Plasma glucose concentration
Blood Pressure: Diastolic blood pressure
Skin Thickness: Triceps skinfold thickness
Insulin: 2-hour serum insulin
BMI: Body mass index
Diabetes Pedigree Function: A measure of genetic diabetes risk
Age: Age in years
Outcome: Diabetes status (1 for positive, 0 for negative)

## Insights and SQL Analysis
SQL queries were employed to extract insights, such as identifying patients with diabetes, examining age-based trends, and analyzing the distribution of diabetes-positive cases. This analysis helps in understanding the dataset's structure and preparing it for machine learning.

## Data Preprocessing
The dataset required preprocessing to handle missing or zero values in critical fields (e.g., Blood Pressure, Insulin). Missing values were replaced with the median to ensure a reliable dataset for training. The data was then split into training and test sets (80/20 ratio).

## Algorithms Used
Three primary machine learning algorithms were implemented and tested:

Decision Tree Classifier: A flowchart-like structure that makes decisions based on feature values.
Artificial Neural Network (ANN): Simulates a human brain structure with interconnected layers for deeper learning, tested with both Single Layer Perceptron (SLP) and Multi-Layer Perceptron (MLP).
Gradient Boosting Classifier: An ensemble learning technique that combines weak learners to create a robust model, aimed at reducing bias and enhancing accuracy.

## Performance Measurement
Performance of each algorithm was measured using various metrics:

Accuracy: Proportion of correctly classified instances.
Precision: Ratio of true positive predictions to total positive predictions.
Recall: Proportion of true positives identified by the model.
Specificity: True negative rate, crucial for models distinguishing between diabetic and non-diabetic cases.
F1 Score: Balance between precision and recall.
These metrics provide insights into each model's effectiveness in predicting diabetes.

## Results and Comparison
The performance of each algorithm was compared using cross-validation and visualized through bar plots. Notable findings include:

Decision Tree Classifier: High training accuracy, but slightly overfit with test accuracy around 85%.
ANN: Performed moderately well but showed limitations due to dataset size.
Gradient Boosting: Achieved the best test accuracy, around 85%, making it the most promising model for this dataset.

## Discussion
The project explored various machine learning models, revealing the benefits and limitations of each. Decision Trees are easy to interpret but may overfit, ANN is powerful but requires larger datasets, and Gradient Boosting offers robust performance with its ensemble approach. Machine learning can be a valuable tool in diabetes prediction, but careful model selection and data preprocessing are essential for accuracy.

## Conclusion
This project demonstrates the utility of machine learning in predicting diabetes. By exploring different algorithms and preprocessing steps, we can create a model that supports early diagnosis and potentially improves patient outcomes. The comparison of multiple algorithms highlights the value of ensemble methods, especially Gradient Boosting, for structured datasets like this one.

## References
- International Diabetes Federation: About Diabetes(http://www.idf.org/about-diabetes)
- IDF: Diabetes Facts & Figures(https://www.idf.org/aboutdiabetes/what-is-diabetes/facts-figures.html)
- WHO: Diabetes Programme (http://www.who.int/diabetes/en/)
- Pima Indians Diabetes Database on Kaggle (https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Computational Intelligence - Module 1 Overview (Noroff)(https://core-noroff.bravais.com/api/dynamic/documentVersions/12442/files/100886/index.html#Item1-12)
- Computational Intelligence - Module Overview (HTML) (bravais.com)(https://core-noroff.bravais.com/api/dynamic/documentVersions/13502/files/111063/index.html#Item1-10)
- Data Pre-Processing - Module 2 Overview (Noroff)(https://core-noroff.bravais.com/api/dynamic/documentVersions/13502/files/111063/index.html#Item1-10)
- Introduction to Data Mining - Module 1 Overview (Noroff)(https://core-noroff.bravais.com/api/dynamic/documentVersions/12442/files/100886/index.html#Item1-12)
- Matplotlib - Visualization with Python(https://matplotlib.org/)
- Replacing Missing Values Using Pandas in Python - GeeksforGeeks (https://www.geeksforgeeks.org/replacing-missing-values-using-pandas-in-python/)
- Decision Trees - Computational Intelligence, Module 2 (Noroff)(https://core-noroff.bravais.com/api/dynamic/documentVersions/13048/files/106817/index.html#Item1-5)
- ANN - Computational Intelligence, Module 3 Overview (Noroff)(https://core-noroff.bravais.com/api/dynamic/documentVersions/13048/files/106817/index.html#Item1-5)
- Ensemble Technique - Noroff Module Overview (https://core-noroff.bravais.com/api/dynamic/documentVersions/13048/files/106817/index.html#Item1-5)
- Jupyter Notebook: An Introduction – Real Python(https://realpython.com/jupyter-notebook-introduction/)
- Yoga in Daily Life(https://yogaindailylife.org/)
