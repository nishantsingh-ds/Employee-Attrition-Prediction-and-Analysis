# Employee Attrition Prediction

## Project Overview

This project aims to analyze and predict employee attrition within an organization using machine learning techniques. The goal is to identify key factors contributing to employee turnover and develop models that can accurately predict whether an employee is likely to leave the company. By leveraging these insights, organizations can implement targeted retention strategies, reduce turnover costs, and improve overall employee satisfaction.

## Key Steps and Methodology

1. **Data Preprocessing and Feature Engineering**
   - Cleaned and preprocessed the dataset, handling missing values, encoding categorical variables, and normalizing continuous features.
   - Created new features such as tenure and age brackets to enhance the model's predictive power.

2. **Exploratory Data Analysis (EDA)**
   - Conducted EDA to understand the relationships between variables, identifying key factors influencing attrition such as age, monthly income, and total working years.
   - Visualized distributions, correlations, and attrition rates across different employee segments.

3. **Model Development and Tuning**
   - Developed multiple machine learning models including Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, AdaBoost, and Gradient Boosting to predict employee attrition.
   - Performed hyperparameter tuning using GridSearchCV to optimize model performance.

4. **Model Evaluation**
   - Evaluated models using metrics such as accuracy, precision, recall, F1-score, and specificity.
   - Compared models based on their ability to correctly identify instances of attrition (class 1) and overall predictive performance.

5. **Feature Importance Analysis**
   - Analyzed feature importance for tree-based models, identifying the most influential factors contributing to employee attrition.
   - Visualized feature importance to provide actionable insights for HR management.

6. **Final Model Selection**
   - Selected the best-performing model based on a balance of accuracy, specificity, and performance on class 1 (attrition cases).
   - The Logistic Regression model was chosen for its high testing accuracy (88.10%) and interpretability, making it suitable for HR decision-making.

## Results and Insights

- **Accuracy and Specificity:** The Logistic Regression model achieved the highest testing accuracy (88.10%) and decent specificity (88.30%), making it the best overall performer for this task.
- **Key Factors:** Age, monthly income, and total working years were identified as the most significant predictors of employee attrition.
- **Actionable Insights:** The analysis provided valuable insights into employee segments with higher attrition risks, allowing the organization to design targeted retention strategies.

## Future Work

- Explore advanced models like XGBoost and neural networks for potentially higher predictive performance.
- Implement explainable AI techniques to enhance model transparency and stakeholder trust.
- Extend the analysis to include real-time monitoring and prediction of employee attrition using continuous learning models.

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Machine Learning Algorithms: Logistic Regression, KNN, Decision Tree, Random Forest, AdaBoost, Gradient Boosting

