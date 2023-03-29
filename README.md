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

### I found some interesting insights:

**1. Based on the provided statistics for the bank's clients in different countries, here are some useful notes that could be made:**

The proportion of exited clients varies significantly between countries, with France having the highest proportion (810/5014 = 16.14%), followed by Germany (814/2509 = 32.46%), and Spain having the lowest proportion (413/2477 = 16.69%).

Germany has the largest absolute number of exited clients (814), even though it has fewer clients overall than France and Spain.

The number of non-exited clients in France is much larger than in Spain and Germany, which could suggest that France is a key market for the bank.

It would be useful to investigate further why the proportion of exited clients is higher in Germany compared to France and Spain, as this could indicate potential issues with customer retention or satisfaction in Germany.

The bank could potentially use this information to focus on improving customer retention in countries where the proportion of exited clients is higher, or to invest in growth in countries where the number of non-exited clients is larger.

Overall, these statistics provide some useful insights into the bank's customer base in different countries, and could help inform future business decisions.

**2. Banks may lose their high age and high balance clients due to a variety of factors, including:**

Poor customer service: If high balance clients feel that they are not receiving adequate customer service from their bank, they may decide to switch to another bank that offers better service.

Inflexible products and services: Older clients may have unique financial needs and priorities, such as retirement planning, estate planning, or long-term care. If their bank cannot provide the necessary products and services to meet these needs, they may look elsewhere.

Technology and digital literacy: Older clients may be less comfortable with technology and digital banking services, which can make it more difficult for them to manage their accounts or access their funds. Banks that do not provide sufficient support or training for these clients may risk losing them to competitors that offer more user-friendly interfaces.

Lack of personalized attention: High balance clients may feel that their bank does not provide enough personalized attention or customized services that meet their unique financial needs.

High fees and charges: Banks may charge high fees and transaction costs for maintaining high balance accounts, which can be a turn-off for some clients.

Better offers from competitors: High balance clients may receive better offers and incentives from other banks or financial institutions, such as higher interest rates, lower fees, or more favorable loan terms.

### Conclusion
**Based on the results of the churn modeling for the bank customers using several models, we can conclude that all models have a good level of accuracy in predicting whether a customer will exit or not. The random forest model achieved an accuracy of 87.4% with a recall of 97 and 49 and a precision of 92 and 61. On the other hand, the lightboost model achieved an accuracy of 87% with a recall of 96 and 53 and a precision of 92 and 63.**

**From the perspective of the bank, it is important to identify customers who are likely to exit so that they can take appropriate measures to retain them. In this case, the higher True negative score of the models is more important.**

**Overall, the lightboost model may be a better choice for the bank as it has a higher recall score and a slightly higher precision score, which indicates that it is better at identifying customers who are likely to exit while still being able to identify a reasonable number of customers who are likely to stay.**

Security concerns: High balance clients may be concerned about the security of their funds and personal information, especially if the bank has a history of security breaches or cyber attacks.

Changes in financial needs: High balance clients may experience changes in their financial needs and priorities over time, such as a change in their investment strategy or a shift in their spending habits. If their bank cannot provide the necessary services to meet these changing needs, they may look elsewhere.

Overall, retaining high age and high balance clients requires banks to provide personalized attention, innovative products and services, user-friendly technology, and exceptional customer service that meets the unique needs and preferences of these clients.
