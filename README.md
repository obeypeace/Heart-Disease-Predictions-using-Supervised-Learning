# Heart-Disease-Predictions-using-Supervised-Learning
Welcome to the Heart Disease Prediction project repository! This project aims to develop a machine learning model that can predict the likelihood of a person having heart disease based on various medical features. By leveraging supervised learning techniques and advanced analytics, we seek to assist healthcare professionals in early detection and prevention of heart disease, ultimately improving patient outcomes and quality of life.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
The objective of this project is to utilize supervised learning techniques to build a machine learning model capable of predicting the likelihood of a person having heart disease based on various medical features. This predictive model aims to assist healthcare professionals in early detection and prevention of heart disease, ultimately contributing to improved patient outcomes and quality of life.

## Data Source
The dataset used for this analysis was obtained from 10Alytics. The heart disease dataset used in this project comprises 303 records and 14 columns, including the target variable. The dataset contains essential medical features such as age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest (oldpeak), the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy (ca), and thalassemia (thal). This dataset serves as the foundation for training and evaluating the machine learning model.

## Data Processing
Before training the machine learning model, the dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features. Exploratory data analysis (EDA) techniques are applied to gain insights into the distribution and relationships between different features. Additionally, the dataset is split into training and testing sets to evaluate the model's performance.

## Evaluation Metrices
To assess the performance of the machine learning model, several evaluation metrics are utilized, including accuracy, precision, recall, and ROC AUC score. These metrics provide insights into the model's ability to correctly classify individuals with and without heart disease, enabling healthcare professionals to make informed decisions based on the model's predictions.

## key Insights
1. Majority of the hospital's patient fall into the Adult (36 -55) age bracket. The youth (<= 35) age bracket have the least count in the hospital's record.
2. Majority of the patients at the hospital are male. More males have heart disease than females
3. Most of the patients (143) are diagnosed with Asymptomatic chest pain type while only 23 of the patients have Non-angina pain. Patients with Atypical angina type of chest pain have a higher proportion of heart disease diagnosis than the other types of chest pain
4. 165 of the hospital's patient have heart diseases wwhile 138 of the patients do not have any heart disease.
5. The adult (36-55) age bracket have more patients with heart disease while the Youth (<= 35) have the least amount of patients with heart disease.
6. The target feature (tells if a patient have heart disease or not) have a (weak) positive correlation only with the chest-pain-type, st_slope, rest_ecg, max_heart_rate features.
7. 8 models were used employed in this project. When compared to the other models metrics, the Naive Bayes Model has the best result for the confusion matrix.
- The model predicted that 27 people have heart disease and 26 people do not have heart disease.
- It predicted that 5 patient do not have heart disease which is not so in the actual dataset.
- It predicted that 3 patient have heart disease which is false in the actual dataset
8. Looking at the metrics employed in this project:
- Accuracy: Naive Bayes has the highest accuracy at 86.89%, followed closely by Random Forest and Decision tree, both at 85.25%.
- Precision: Decision tree has the highest precision at 92.59%, followed by Naive Bayes at 90.00% and XGB Classifier at 86.21%.
- Recall: Random Forest has the highest recall at 87.50%, followed by Naive Bayes at 84.38% and XGB Classifier at 78.12%.
- ROC AUC: Naive Bayes has the highest ROC AUC at 87.02%, followed by Decision tree at 85.61% and Random Forest at 85.13%.

## Conclusion and Recommendations
Considering these metrics, Naive Bayes seems to perform consistently well across all metrics and could be a strong candidate for selection.
