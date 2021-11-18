# T5-Final-prject
manar almohaimeed 
# Design

This project is one of the T5 Data Science BootCamp requirements. Data provided by Kaggle has been used in this project.
We will analyze the data to find the relation between the features and use machine learning algorithms that would enable us to predict
if the patient has cardiovascular disease or not.

# Data
The dataset is provided in .csv format. It contains of 70,000 patient record with 13 features for each patients doing cardiovascular disease examination. 
All of the dataset values were collected at the moment of medical examination.
There are 3 types of input features:Objective: factual information, Examination: results of medical examination, and Subjective: information given by the patient.
here are the sample of data set :

![cardio](https://user-images.githubusercontent.com/93050714/142349238-59f50a7e-c15c-4c1c-8f99-4c32f8b6b297.png)

The feature list:
- Age | Objective Feature | age | int (days)
- Height | Objective Feature | height | int (cm) |
- Weight | Objective Feature | weight | float (kg) |
- Gender | Objective Feature | gender | categorical code | 1:women, 2:men
- Systolic blood pressure | Examination Feature | ap_hi | int |
- Diastolic blood pressure | Examination Feature | ap_lo | int |
- Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
- Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
- Smoking | Subjective Feature | smoke | binary |
- Alcohol intake | Subjective Feature | alco | binary |
- Physical activity | Subjective Feature | active | binary |
- Presence or absence of cardiovascular disease | Target Variable | cardio | binary |  

# Algorithms

Cleaning the data by converting the Hight from CM to M, age from days to year, and changing the data type to integer.
 ,Calculating the BMI by applying this formula (wight / height^2) 
, Finding the most age affecting the occurrence of cardiovascular disease, Find if smoke affects the occurrence of cardiovascular disease?
 ,The gender that most suffer from cardiovascular diseases
 
![صورة2](https://user-images.githubusercontent.com/93050714/142351172-4541e902-aec2-4648-9c95-b628558ae597.png)


**Models**
Logistic Regression, and random forest were used in this projest. The random forest get the higher accuracy .

**Model Evaluation and Selection**
Logistic Regression, and random forest were used to molding the data . The random forest get the higher accuracy . The models were trained on a 25/75 test vs. train. The official metric was the accuracy of the model, where the model tested on the accuracy.

The result of used model:

•	Accuracy:72.2%

# Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and Seaborn for plotting
- LogisticRegression and RandomForestClassifier for modling

# Communication
The slides are provided here.

