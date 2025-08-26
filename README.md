Project Title: BALAJI FAST FOOD SALES ANALYSIS

About Dataset

Balaji Fast Food is a small fast-food restaurant located in India. The restaurant sells a variety of items such as snacks, main dishes and beverages. Transactions are recorded on a daily basis, capturing sales details of each item sold.
The dataset represents the point-of-sale (POS) records of the restaurant over a certain time period. It includes details about items, sales amount, staff handling the order, and payment mode

Dataset Summary
Row Count: 1000
Column: 10

order_id : Unique identifier for each order

date : Unique identifier for each order

item_name : Name of the item sold

item_type  : Category of the item

item_price  : Price of a single unit of the item

quantity  : Number of units sold in that transaction

transaction_amount  : Total bill amount of the order

transaction_type  : Payment mode (e.g., Cash, Online)

received_by  : Staff member who handled the transaction

time_of_sale : Time slot of the transaction (Morning, Afternoon, Evening, Night)

Project Steps and Objectives: 

1)Data Loading and Initial Overview

Read the HOSPITAL PATIENT RECORDS data from the CSV file into a pandas DataFrame.                   

Print the first few rows of the dataset to get an overview of the data. 

Obtain the number of rows and columns in the dataset. 

Get a concise summary of the dataset, including the data types and non-null values. 

Generate descriptive statistics for numerical columns. 

Print the Data types of each columns.

2)Data Pre-Processing

Find and count the null datas in the dataset.

Handling Missing Values with mode

Removing duplicates

Convert date format to YYY-MM-DD

To insert "profit" column based on "transaction_amount" column. 

3)Exploratory Data Analysis (EDA) & Visualization

Univariate Visualization - 


a)Histogram for Profit Distribution


b)Box Plot for Profit by Item Type


c)Pie Chart for Transaction Type Distribution

Bivariate Visualization - 


a)Scatter plot for Item Price vs Quantity


b)Correlation Heatmap Between Item Price, Quantity, Transaction Amount and Profit

Multivariate Visualization - 


a)Pair Plot for Item Price, Quantity, Transaction Amount and Profit


b)Line Chart for Daily Sales Trend


Aggregated Data Visualization - 


a) Bar Plot for Top 10 Items by Quantity


b) Count Plot for Number of Transactions by Staff


c)  Violin Plot for Transaction Amount by Transaction Type


d) Bar Plot for Total Profit by Time of Sale


e) KDE Plot for Profit Distribution


f)  Skewness Analysis for Profit


4)Final Busiess Insights
