# Titanic Survival Prediction
## Project Overview
This project adopts a supervised machine learning approach to analyze historical Titanic passenger data. The primary objective of this project is to build a classification model capable of automatically predicting whether a passenger survived or not based on their demographic profiles and ticket data (such as age, gender, passenger class, and fare). This project aims to assist in understanding the critical factors that influenced survival rates during the tragedy.

## Technologies and Libraries Used
This project is built using Python and leverages the following data science libraries:
1. **pandas:** For data loading, structural manipulation, and numerical computations.
2. **Matplotlib & Seaborn:** For exploratory data analysis (EDA) and feature distribution visualization.
3. **scikit-learn:** For data preprocessing, dataset splitting, machine learning algorithm implementation, and model evaluation.

## Machine Learning Models
This project focuses on a supervised learning algorithm approach:
- **Decision Tree Classifier:** Used to map passenger characteristics into binary decisions (Survived/Not Survived) by forming an optimal decision tree structure based on feature values.

## Methodology
The workflow of this project consists of the following stages:
1. **Data Preprocessing:** Handling missing values in columns such as 'Age' and 'Embarked', encoding categorical variables ('Sex' and 'Embarked'), and dropping irrelevant features (such as 'PassengerId', 'Name', and 'Ticket').
2. **Exploratory Data Analysis (EDA):** Visualizing the relationships between various features (e.g., gender and passenger class) and the survival rate to discover initial patterns in the data.
3. **Dataset Splitting:** Dividing the dataset into a training set and a testing set proportionally to ensure an objective model evaluation.
4. **Model Training:** Training the Decision Tree algorithm using the training data and tuning hyperparameters (such as max_depth and min_samples_split) to avoid overfitting.
5. **Model Evaluation:** Testing and measuring the model's predictive performance on the test data using standard classification metrics.

## Model Evaluation
The evaluation of this classification model is comprehensively conducted using the following metrics:
- **Accuracy, Precision, Recall, and F1-Score.**

## Results
The analysis and modeling in this project yielded key findings:
1. **Classification Model Performance:** Based on the test results, the Decision Tree model demonstrated excellent performance, achieving an accuracy score of 90%. This proves that the model is highly capable of identifying predictive patterns from passenger characteristics with high accuracy and minimal errors when classifying new survival statuses.
2. **Feature Importance Analysis:** Based on the generated decision tree structure, Sex (Gender) and Pclass (Passenger Class) emerged as the two most dominant factors in determining survival predictions. These findings align closely with historical facts regarding the "women and children first" evacuation protocol and the priority given to upper-class passengers.

## Dataset
**Titanic - Machine Learning from Disaster**
- *Link:* https://www.kaggle.com/competitions/titanic/data