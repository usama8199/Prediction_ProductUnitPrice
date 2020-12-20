# Prediction_ProductUnitPrice
This is the part of the Great India Hackathon where we have to predict the unit price of the products using different variables.
The current pandemic has dwindled the data science job market likewise recruiters are also facing difficulties filtering the right talent. To bridge this gap we bring a chance for the MachineHack community to compete for jobs with some of the key analytics players for a rewarding career in Data Science. In this competition, we are challenging the MachineHack community to come up with an algorithm to predict the price of retail items belonging to different categories. Foretelling the Retail price can be a daunting task due to the huge datasets with a variety of attributes ranging from Text, Numbers(floats, integers), and DateTime. Also, outliers can be a big problem when dealing with unit prices.

**** Top 50 Rank

# Overview
1. Cleaned the data by removing the outliers, covert date data to datetime data type, check for data validity, etc
2. Analyze the data with respect to UnitPrice how is unit price is changing on different variables like store location, quantity etc
3. Predicted the data with Extra Tree Regressor with low RMSE
4. Optimize using Genetic Algorithm
5. Came in the Top 50 rank

# Data Dictionary
    Invoice No - Invoice ID, encoded as Label
    StockCode - Unique code per stock, encoded as Label
    Description - The Description, encoded as Label
    Quantity - Quantity purchased
    InvoiceDate - Date of purchase
    UnitPrice - The target value, price of every product
    CustomerID - Unique Identifier for every Customer
    Country - Country of sales, encoded as Label
    

