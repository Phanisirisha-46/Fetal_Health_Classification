# Fetal Health Classification 

## Overview

This project involves classifying fetal health based on various features extracted from a dataset. The aim is to use machine learning techniques to predict the health status of the fetus from the available data.

## Dataset

The dataset used for this project is the fetal health dataset, which includes 2126 samples and 22 features. These features encompass various aspects related to fetal health, such as baseline value, accelerations, fetal movement, uterine contractions, and more.

## Features

1. **Baseline Value**: Baseline fetal heart rate.
2. **Accelerations**: Number of fetal heart rate accelerations.
3. **Fetal Movement**: Frequency of fetal movements.
4. **Uterine Contractions**: Number of uterine contractions.
5. **Light Decelerations**: Number of light decelerations in fetal heart rate.
6. **Severe Decelerations**: Number of severe decelerations.
7. **Prolonged Decelerations**: Number of prolonged decelerations.
8. **Abnormal Short-Term Variability**: Measure of short-term fetal heart rate variability.
9. **Mean Value of Short-Term Variability**: Average value of short-term variability.
10. **Percentage of Time with Abnormal Long-Term Variability**: Percentage of time with abnormal long-term variability.
11. **Histogram Features**: Includes histogram minimum, maximum, and number of peaks.

## Methodology

1. **Data Preprocessing**: 
   - Handle missing values using imputation techniques.
   - Normalize or standardize the data if necessary.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the data using plots and graphs to understand patterns and relationships.

3. **Model Building**:
   - Split the dataset into training and testing sets.
   - Train various machine learning models such as Logistic Regression, Linear Regression, etc.
   - Evaluate the models using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

4. **Model Evaluation**:
   - Assess the performance of models using the testing set.
   - Compare model performance and select the best-performing model based on evaluation metrics.

5. **Results**:
   - Present the results of model performance, including accuracy and other relevant metrics.
   - Discuss the implications of the results and their potential impact on fetal health classification.

## Tools and Libraries

- **Python Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Google Colab**: For running and sharing the notebook
