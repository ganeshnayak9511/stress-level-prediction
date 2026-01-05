# stress-level-prediction
A machine learning model for predicting stress levels using psychological, health, environmental, academic, and social factors. The project compares Decision Tree, Logistic Regression, and Random Forest models, with Random Forest achieving the best performance.

# Dataset Overview

•	Total Records: 1100
•	Total Features: 21
•	20 input features
•	1 target variable

# Feature Categories
•	Psychological: anxiety_level, depression, self_esteem
•	Health: blood_pressure, headache, breathing_problem
•	Environmental: noise_level, living_conditions, safety
•	Academic: study_load, academic_performance
•	Social: peer_pressure, social_support, bullying
•	Target Variable: stress_level

# Machine Learning Models Used
1. Decision Tree Classifier
•	Accuracy: 89%
•	Observations:
o	Performs well on training data
o	Tends to overfit when patterns are similar
o	Some confusion between closely related stress classes

2. Logistic Regression
•	Accuracy: 89%
•	Observations:
o	Stable and consistent predictions
o	Simpler linear model
o	Slight underfitting on complex feature interactions

3. Random Forest Classifier (Best Model)
•	Accuracy: 91%
•	Observations:
o	Highest accuracy among all models
o	Handles complex patterns effectively
o	Reduces overfitting by averaging multiple decision trees
o	Best generalization performance

# Best Model Selection
Based on comparative analysis:
•	Random Forest is the most reliable model for predicting stress levels.
•	It achieves the best balance between bias and variance.
•	Recommended for real-world stress level prediction tasks

