# Credit-Card-Default-Predictor

##### This project depends on the CPSC 330 Course Environment Requirements, available [here](https://github.com/UBC-CS/cpsc330-2024W2/tree/main), I would like to express my gratitude to Professor Giulia Toti for designing the assignment this project was extended from and all course materials.

## Introduction <a name="in"></a>
In today’s data-driven world, the ability to predict customer behavior is a critical tool for businesses, especially in industries like finance where accurate predictions can mitigate risk and optimize decision-making. One such application is in credit risk assessment, where financial institutions aim to predict whether a client will default on their credit card payments. Early identification of high-risk clients allows lenders to take proactive measures, such as adjusting credit limits or offering tailored repayment plans, thereby reducing potential losses.

This project focuses on building a robust machine learning pipeline to predict whether a credit card client will default on their payment obligations using the Default of Credit Card Clients Dataset . The dataset contains 30,000 examples and 24 features that capture various aspects of a client's financial behavior, including demographic information, credit usage patterns, and repayment history over six months (April 2005 to September 2005). The target variable, default.payment.next.month, indicates whether a client defaulted in the subsequent month, making this a binary classification problem.

The project is structured to simulate a real-world data science workflow, encompassing several key stages:

1. Exploratory Data Analysis (EDA): Understanding the structure, distributions, and relationships within the data to uncover insights and identify potential challenges, such as ambiguous categories in categorical features (e.g., "education" and "marriage").
2. Data Preprocessing: Cleaning and transforming the data to ensure it is suitable for modeling. This includes handling missing values, encoding categorical variables, scaling numerical features, and addressing class imbalance if present.
3. Feature Engineering: Enhancing the predictive power of the dataset by creating new features or modifying existing ones. For example, temporal trends in repayment behavior and bill amounts may be leveraged to extract meaningful patterns.
4. Model Development: Training and evaluating a range of models, from simple linear models to advanced ensemble techniques such as gradient boosting and random forests. 
5. Hyperparameter Optimization: hyperparameter tuning to optimize performance.
6. Feature Selection and Importance: Identifying the most influential features for predicting defaults, which not only improves model interpretability but also provides actionable insights for stakeholders.
7. Evaluation and Results: Assessing model performance on a held-out test set using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. A comprehensive analysis of results ensures that the chosen model balances predictive accuracy with practical applicability.
