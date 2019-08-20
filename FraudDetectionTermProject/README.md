Along with the great increase in online mobile money transactions, fraud has become increasingly rampant in recent years. Fraud is one of the major causes of great financial losses and financial institutions are advancing their capability to detect fraud.
The objective of this project is to develop machine learning model to detect fraud.

Along with the great increase in online mobile money transactions, fraud has become increasingly rampant in recent years. Fraud is one of the major causes of great financial losses and financial institutions are advancing their capability to detect fraud.
The objective of this project is to develop machine learning model to detect fraud.

Financial Fraud Detection using Decision Tree and Random Forest Machine Learning Models

Along with the great increase in online mobile money transactions, fraud has become increasingly rampant in recent years. Fraud is one of the major causes of great financial losses and financial institutions are advancing their capability to detect fraud.
The objective of this project is to develop machine learning model to detect fraud.

In this notebook, we will showcase the use of decision tree and  Random Forest ML models to perform financial fraud detection.
This project is done as a group for SCS_3253_029 Machine Learning in UofT for DataScience

# Project Members
Vijayan Alagudevan 
Sabarinathan Selvaraj
VinodH KUMAR AIYAPPAN
SATISH SUBRAMANIAN

### Source Data
PaySim simulates mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The original logs were provided by a multinational company, who is the provider of the mobile financial service which is currently running in more than 14 countries all around the world.

This [synthetic dataset](https://www.kaggle.com/ntnu-testimon/paysim1) is scaled down 1/4 of the original dataset and it is created just for Kaggle.  To load the dataset yourself, please download it to your local machine from Kaggle and then import the data via **Import Data**: [Azure](https://docs.azuredatabricks.net/user-guide/importing-data.html#import-data) | [AWS](https://docs.databricks.com/user-guide/importing-data.html#import-data).

### Dictionary
This is the column definition of the referenced sythentic dataset.

| Column Name | Description |
| ----------- | ----------- | 
| step | maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).|
| type | CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER. |
| amount |  amount of the transaction in local currency. |
| nameOrig | customer who started the transaction |
| oldbalanceOrg | initial balance before the transaction |
| newbalanceOrig | new balance after the transaction |
| nameDest | customer who is the recipient of the transaction |
| oldbalanceDest | initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants). |
| newbalanceDest | new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants). |

