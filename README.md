# Titanic Survival Prediction using Logistic Regression
Project Overview

This project predicts passenger survival on the Titanic using Logistic Regression. The workflow covers data exploration, preprocessing, feature engineering, model building, and hyperparameter tuning.

# 1. Dataset

Source: Kaggle Titanic dataset

Target variable: Survived (0 = did not survive, 1 = survived)

Features: Numerical (Age, Fare, SibSp, Parch) and Categorical (Sex, Pclass, Embarked)

# 2. Exploratory Data Analysis (EDA)

Examine dataset shape, information, and missing values.

Analyze distributions of numerical features (Age, Fare).

Check survival rate by gender, passenger class, and age groups.

Identify correlations between features and target variable.

# 3. Feature Engineering

Handle missing values in Age and Embarked.

Encode categorical variables like Sex, Embarked, and Pclass.

Create new features such as FamilySize = SibSp + Parch + 1.

Drop unnecessary columns like Name, Ticket, and Cabin.

# 4. Feature Scaling

Apply standard scaling to numerical features to normalize values.

# 5. Logistic Regression Model

Build a baseline Logistic Regression model.

Split data into training and testing sets.

Evaluate model using accuracy, confusion matrix, and classification metrics.

# 6. Hyperparameter Tuning
GridSearchCV

Test all possible parameter combinations to find the optimal model.

RandomizedSearchCV

Test a random subset of parameter combinations to quickly find a near-optimal model.

Compare GridSearchCV and RandomizedSearchCV results to select the best model.

# 7. Evaluation

Evaluate final model using:

## Accuracy

Precision, Recall, F1-Score

# 8. Conclusion

Logistic Regression is effective for predicting Titanic survival.

Feature engineering and scaling improve model performance.

Hyperparameter tuning optimizes the model further.
