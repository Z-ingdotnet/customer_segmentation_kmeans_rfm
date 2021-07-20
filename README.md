# customer_segmentation_kmeans_rfm.ipynb
Advanced Customer Segmentation using Kmeans and RFM with Python

Dataset
The data is customer transaction,containing

different meta data about offer and award
demographic data for each customer
records for transactions, amount of offers received, reinvestment amount and ratio etc

Data has been summarized and prepared via MSSQL for final analysis

customerID (string) - customer id

CustomerLTVScore (float) - predicted customer life time value

loyaltypointsbalance (int) - Total loyalty points remaining

LTSPEND (int) - Customer life time spend

R6LocationPreference (string) - Customer store location preference in the past 6 months

LT_Roomoffergiven (int) - free room offer given for customer all time

LT_RI	(float) - customer life time reinvestment ratio

R12_Roomoffergiven	- free room offer given for customer in the past 12 months

R3_RI - customer reinvestment ratio in the past 3 months

R6_spend - Customer spend in the past 6 months

R6_Roomoffergiven	- free room offer given for customer in the past 6 months

R6_RI - customer reinvestment ratio in the past 6 months

R3_spend - Customer spend in the past 3 months

R3_Roomoffergiven	- free room offer given for customer in the past 3 months

R3_RI - customer reinvestment ratio in the past 3 months

LT_sepnd - Monetary Value

LT_Freqcount - Frequency

Recency - Recency

age (int) - age of the customer

Tenune (int) - days since when customer created an account
