# casestudy
## Project Description

This project focuses on predicting successful credit card transactions for online purchases in DACH countries (Germany, Austria, Switzerland). The goal is to analyze credit card transaction data and predict whether a payment will be successful or fail. The dataset includes information from different Payment Service Providers (PSPs) and accounts for multiple payment attempts for the same purchase.

## Dataset

The dataset provided includes credit card transactions from January to February 2019. The key features include:

- **tmsp**: Timestamp of the transaction
- **country**: Country of the transaction (Germany, Austria, Switzerland)
- **amount**: Transaction amount
- **success**: 1 if the payment was successful, 0 if it failed
- **PSP**: Payment Service Provider (e.g., Moneycard, Goldcard, UK_Card, Simplecard)
- **3D_secured**: Indicates if the transaction was 3D-secured (more secure online payment)
- **card**: Credit card provider (MasterCard, Visa, Diners)

### Business Context

- Multiple payment attempts can occur for the same purchase. If two transactions are within one minute, have the same amount, and come from the same country, they are likely part of the same purchase attempt.
- The model should consider multiple payment attempts for the same purchase when making predictions.

## Objective

- Predict whether a credit card transaction will be successful or fail.
- Analyze the factors influencing payment success or failure.
- Handle multiple attempts for the same purchase in the model.

## How to Use

1. Download the dataset and unzip the files.
2. Preprocess the data (e.g., handle missing values, encode categorical variables).
3. Build a predictive model (e.g., using machine learning algorithms like logistic regression or decision trees).
4. Evaluate the model's performance and deploy it for real-time predictions.

## Installation

Clone the repository and install dependencies:
