# Obesity-Levels-Prediction-ML-Project
This is my midterm project which is part of DAT402 at Arizona State University

## 📌 Brief Summary:
The Obesity Levels Prediction project aimed to analyze individuals' eating habits, physical condition, and lifestyle factors to classify their obesity levels using machine learning models. The project was based on a dataset from the UCI Machine Learning Repository, which contained multiple health-related attributes such as BMI, calorie consumption, water intake, and physical activity levels. The main goal was to create a predictive model that could effectively determine a person's obesity category, ranging from underweight to morbidly obese​.

## 🔧 Tools & Technologies Used:

### Programming Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Machine Learning Algorithms:
Naïve Bayes (initial model)
Decision Trees
Support Vector Machines (SVM)
Random Forest (best-performing model)

### Data Preprocessing Techniques:
Feature selection
Handling missing values
Standardization and normalization

## 📊 Results & Key Findings:
Initially, the Naïve Bayes model performed unexpectedly well, but further analysis revealed potential issues with overfitting and data leakage. The model's confusion matrix showed unrealistically perfect results, prompting a feature selection approach. After adjusting the model, the final accuracy improved to 52%, which was higher than the baseline 14% accuracy expected from a random classifier​.

## Key insights included:
Higher BMI and calorie intake correlated strongly with obesity.
Sedentary lifestyles and poor hydration were major contributors to weight gain.
Feature engineering played a crucial role in improving the model’s generalization ability.
