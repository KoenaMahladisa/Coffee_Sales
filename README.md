# Coffee_Sales
Predictions for coffee sales
Coffee generate valuable transaction data that can be used to understand customer purchasing behaviour, identify popular products, and support better inventory and product-management decisions. However, analysing thousands of transactions manually can make it difficult to identify meaningful purchasing patterns and relationships between transaction characteristics and coffee preferences.

This project analyses coffee transaction data to explore customer purchasing patterns and investigate whether machine learning can be used to predict the type of coffee purchased. The dataset contains 2,838 transaction records with information relating to the transaction date and time, payment method, card identifier, amount spent, and coffee product purchased.

The analysis combines exploratory data analysis (EDA), data preprocessing, feature engineering, data visualisation, and machine learning. Transaction dates and times are transformed into useful features such as the hour, day, and month of purchase. Missing values in the card identifier field are also handled during the data-cleaning process.
The machine-learning component uses a Random Forest Classifier to predict the coffee_name based on available transaction-related features. The project evaluates the classification model using accuracy and a classification report.

Project Objectives
