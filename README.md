# Heart-Disease-Prediction-Using-Python-Machine-Learning

## Table of Contents

1. [Introduction](#introduction)

2. [Dataset](#dataset)

3. [Technologies Used](#technologies-used)

4. [Data Preprocessing](#data-preprocessing)

5. [Model Training](#model-training)

6. [Model Evaluation](#model-evaluation)

7. [How to Use](#how-yo-use)

8. [Results](#results)

9. [Conclusion](#conclusion)

## 1. Introduction

Heart disease remains one of the leading causes of mortality worldwide. Early detection of heart disease can help in taking preventive measures. This project utilizes machine learning techniques to predict whether a person has heart disease based on various health parameters.

## 2. Dataset

The dataset used in this project consists of 1025 instances with 13 features and 1 target variable:

- Features include age, sex, chest pain type (cp), blood pressure (trestbps), cholesterol level (chol), fasting blood sugar (fbs), resting ECG results (restecg), maximum heart rate (thalach), exercise-induced angina (exang), ST depression (oldpeak), slope, number of major vessels (ca), and thalassemia (thal).

- The target variable is 0 (No Heart Disease) or 1 (Heart Disease Present).

Heart_csv dataset preview - the first five rows of the dataset;

![image_alt](https://github.com/Shamiso-Tirivanhu/Heart-Disease-Prediction-Using-Python-Machine-Learning/blob/88b71aaf228d64687ccbf00b9aa868783ac3a3ee/A%20data%20preview%20-%20first%205%20rows%20of%20the%20dataset.png)





Heart_csv dataset preview - the first five rows of the dataset;

![image_alt](https://github.com/Shamiso-Tirivanhu/Heart-Disease-Prediction-Using-Python-Machine-Learning/blob/c3f489168359a69a66f45f5c00cab34ba567acfd/A%20data%20preview%20-%20the%20last%20give%20rows%20of%20the%20dataset.png)

## 3. Technologies Used

- Python

- Pandas
  
-  NumPy

- Scikit-learn

## 4. Data Preprocessing

- Loading the dataset: The dataset is loaded using Pandas.

- Checking missing values: No missing values were found in this dataset.

- Splitting features and target: The dataset is divided into features (X) and target variable (Y).

- Splitting into train-test sets: The dataset is split into 80% training and 20% testing data.

## 5. A Logistic Regression model was used for classification. The steps include:

- Training the model on X_train and Y_train.

- Predicting outcomes using the trained model.

## 6. To evaluate performance, we used:

Accuracy Score:

- Training accuracy: 85.24%

- Testing accuracy: 80.48%

The only matrix that was deployed in this project was accuracy_score. It was used to ascertain whether the training and test data is accurate and correspond with each other.

## 7. How to Use

1. Clone the repository.

2. Install dependencies using:

 | pip install -r requirements.txt |
|------------------------------------|

3. Run the model using:

| python heart_disease_model.py |
|-------------------------------|

4. Input test values to predict heart disease presence.

## 8. Results

The model demonstrated a good accuracy of 80.48% on test data, making it a viable tool for preliminary heart disease screening.

The accuracy score metrics was deployed and below is the performance of the dataset on both training & test data;

![image_alt](https://github.com/Shamiso-Tirivanhu/Heart-Disease-Prediction-Using-Python-Machine-Learning/blob/894d2c00336f0d6fcf976593dfe3954c32c11b71/Accuracy%20score%20metrics%20-%20performance%20of%20the%20model.png)

## 9. Conclusion

This project highlights the power of machine learning in medical diagnosis. However, the dataset used in this project is relatively small, which affects the accuracy of the model. A larger dataset would likely improve the predictive power and generalizability of the model.
