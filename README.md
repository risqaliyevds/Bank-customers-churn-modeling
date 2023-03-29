## Bank customers churn modeling

This notebook demonstrates how to use machine learning to predict customer churn for a bank. Customer churn is the phenomenon of customers leaving the bank and closing their accounts. It is a costly problem for the business and needs to be addressed effectively.

### The project follows these steps:

- **Data Preprocessing:** The notebook imports the necessary libraries and loads the data. It checks for missing values, duplicates, outliers, and any other data quality issues. It also performs some basic statistics and visualizations to understand the data better.
- **Exploratory Data Analysis:** The notebook explores the relationship between the target variable (customer churn) and the independent variables (customer features). It uses various plots and statistical tests to identify patterns, trends, and correlations in the data.
- **Feature Engineering:** The notebook creates new features from the existing ones to capture more information and improve model performance. It also selects the most relevant features using feature importance techniques.
- **Model Implementation:** The notebook trains and tests several machine learning models to predict customer churn. It uses different algorithms, such as RandomForestClassifier, GradientBoostingClassifier, XGBClassifier, CatBoostClassifier, and LGBMClassifier. It also applies cross-validation and hyperparameter tuning to optimize the models.
- **Evaluation:** The notebook evaluates the performance of each model using different metrics, such as accuracy, precision, recall, and F1 score. It compares the models and selects the best one based on these metrics. It also plots the confusion matrix and the ROC curve to visualize the model results.
- **Insights and Recommendations:** The notebook interprets the model results and draws insights from them. It identifies the key factors that influence customer churn and makes recommendations to the business on how to reduce churn and increase customer loyalty.

### In conclusion
I compared the performance of different models to predict customer churn for a bank. I concluded that the lightboost model is the best option as it has the highest recall and precision scores, which means it can better identify customers who are likely to exit and stay.
