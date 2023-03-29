## Bank customers churn modeling

### Content
This data set contains details of a bank's customers and the target variable is a binary variable reflecting the fact whether the customer left the bank (closed his account) or he continues to be a customer.

1. Introduction
2. Import libraries
3. Data Preprocessing
4. Exploratory data analysis
5. Feature engineering
6. Model implementation
  - RandomForestClassifier
  - GradientBoostingClassifier
  - XGBClassifier
  - CatBoostClassifier
  - LGBMClassifier
7. Evaluation

### Introduction:
In this notebook, I will be working on a customer churning model. The goal of this project is to predict which customers are likely to churn and why they are doing so. Customer churn is a common problem in many industries, including telecommunications, banking, and e-commerce. It is important to identify customers who are at risk of churning and take appropriate actions to retain them.

To accomplish this goal, I will be using machine learning techniques to build a predictive model. I will start by gathering and exploring data on customer demographics, transaction history, customer support interactions, and any other relevant information. Then, I will preprocess the data to prepare it for modeling, which may involve cleaning, feature engineering, and scaling.

Next, I will train and evaluate several machine learning models to predict customer churn. I will use a variety of metrics to evaluate model performance, including accuracy, precision, recall, and F1 score. Based on these metrics, I will select the best-performing model and fine-tune it to improve its accuracy.

Finally, I will interpret the model results and draw insights from them. I will identify the key features that contribute most to customer churn and make recommendations to the business on how to address these issues.

I found some interesting insights:

**Based on the provided statistics for the bank's clients in different countries, here are some useful notes that could be made:**

The proportion of exited clients varies significantly between countries, with France having the highest proportion (810/5014 = 16.14%), followed by Germany (814/2509 = 32.46%), and Spain having the lowest proportion (413/2477 = 16.69%).

Germany has the largest absolute number of exited clients (814), even though it has fewer clients overall than France and Spain.

The number of non-exited clients in France is much larger than in Spain and Germany, which could suggest that France is a key market for the bank.

It would be useful to investigate further why the proportion of exited clients is higher in Germany compared to France and Spain, as this could indicate potential issues with customer retention or satisfaction in Germany.

The bank could potentially use this information to focus on improving customer retention in countries where the proportion of exited clients is higher, or to invest in growth in countries where the number of non-exited clients is larger.

Overall, these statistics provide some useful insights into the bank's customer base in different countries, and could help inform future business decisions.
