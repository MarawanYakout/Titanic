# Titanic

![RMS_Titanic_3](https://github.com/user-attachments/assets/9a590060-c08c-4bf7-857b-60d8bf00557f)


Predicting chances of survival for the Titanic Ship Incident | Categorizing Males &amp; Females - Lower &amp; Higher Class

This submission employs a Random Forest classifier to predict passenger survival on the Titanic. Key aspects of the approach include:

## Data Preprocessing:

Selected relevant features: Pclass, Sex, SibSp, and Parch.

Applied one-hot encoding using pd.get_dummies() to transform categorical variables into numeric features.

## Modeling:

Utilized a Random Forest classifier with 100 estimators and a maximum depth of 5, ensuring reproducibility with a fixed random state.

# Titanic - Machine Learning from Disaster

## Overview
This project is a Kaggle competition entry for the **Titanic - Machine Learning from Disaster** challenge. The goal is to build a predictive model that determines whether a passenger survived or not based on different features such as age, gender, class, and more.

## Dataset
The dataset contains information about passengers aboard the Titanic, including:
- **Survival** (0 = No, 1 = Yes)
- **Pclass** (Passenger class: 1st, 2nd, or 3rd)
- **Name**
- **Sex**
- **Age**
- **SibSp** (Number of siblings/spouses aboard)
- **Parch** (Number of parents/children aboard)
- **Ticket** (Ticket number)
- **Fare** (Passenger fare)
- **Cabin** (Cabin number)
- **Embarked** (Port of embarkation: C = Cherbourg, Q = Queenstown, S = Southampton)

## Approach
1. **Data Preprocessing:**
   - Handle missing values
   - Convert categorical variables into numerical form
   - Feature engineering to improve predictions
   
2. **Exploratory Data Analysis (EDA):**
   - Visualize data distributions and relationships
   - Analyze survival rates based on different features
   
3. **Model Selection & Training:**
   - Train multiple machine learning models such as:
     - Logistic Regression
     - Random Forest
     - Support Vector Machines (SVM)
     - Gradient Boosting
   - Hyperparameter tuning using GridSearchCV
   
4. **Evaluation:**
   - Compare model performance using accuracy, precision, recall, and F1-score
   - Use cross-validation to ensure model robustness
   
5. **Submission:**
   - Generate predictions for the test dataset
   - Submit the results to Kaggle

## Dependencies
To run the notebook, install the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Results
The best-performing model achieved an accuracy of more than **85%** on the test dataset. Further improvements can be made through feature engineering and ensemble methods.

## Usage
1. Download the dataset from Kaggle: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
2. Open the Jupyter Notebook and run each cell step-by-step.
3. Modify the code to experiment with different models and parameters.

---
##  Model Performance Comparison
```
title Model Accuracy Comparison
"Logistic Regression" : 78
"Random Forest" : 85
"XGBoost" : 88
```



## Survival Rate by Class
| Passenger Class | Survival Rate |    
|----------------|--------------|
| 1st Class      | 63.0%        |
| 2nd Class      | 47.3%        |
| 3rd Class      | 24.2%        |



## Contact
For any questions or suggestions, feel free to reach out!
