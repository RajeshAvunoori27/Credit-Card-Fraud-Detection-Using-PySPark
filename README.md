# Credit-Card-Fraud-Detection-Using-PySPark

## Overview
This project focuses on analyzing credit card transactions to identify and understand fraudulent activities. The primary goal is to develop insights and methods to differentiate between legitimate and fraudulent transactions, thereby enhancing fraud detection mechanisms.

## Dataset
The dataset contains both fraud and non-fraud transactions:

Entries: 10,000 transactions
Merchants: 800 merchants
Columns: 23 columns
*Schema*
The schema defines the structure of the data in the dataset:
- index: Unique Identifier for each row
- trans_date_trans_time: Transaction DateTime
- cc_num: Credit Card Number of Customer
- merchant: Merchant Name
- category: Category of Merchant
- amt: Amount of Transaction
- first: First Name of Credit Card Holder
last: Last Name of Credit Card Holder
gender: Gender of Credit Card Holder
street: Street Address of Credit Card Holder
city: City of Credit Card Holder
state: State of Credit Card Holder
zip: Zip of Credit Card Holder
lat: Latitude Location of Credit Card Holder
long: Longitude Location of Credit Card Holder
city_pop: Credit Card Holder's City Population
job: Job of Credit Card Holder
dob: Date of Birth of Credit Card Holder
trans_num: Transaction Number
unix_time: UNIX Time of transaction
merch_lat: Latitude Location of Merchant
merch_long: Longitude Location of Merchant
is_fraud: Fraud Flag (Target Class)
