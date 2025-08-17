# Loan default risk analysis
Project Overview: This project explores the Loan Default Risk dataset to identify the key factors that contribute to a customer defaulting on their loan. Using a combination of multi-source data, exploratory data analysis (EDA), feature engineering, and simple modeling, this project aims to derive business insights that can help lenders reduce risk and make informed decisions.

Problem Statement: Home Credit, a digital lending platform, wants to improve its risk profiling to reduce loan defaults. This project analyzes client application data, external credit history, payment behavior, and previous loans to uncover patterns associated with default. The goal is to build a complete data-driven risk profile using all available data sources.

The dataset contains 8 main CSV files from different sources:

`application_train.csv`: Main training data, includes demographic and financial details of clients along with TARGET variable.
`application_test.csv`: Same as above but without TARGET column (used for prediction).
`bureau.csv`: Client’s credit history with other institutions.
`bureau_balance.csv`: Monthly updates for each bureau record.
`previous_application.csv`: Records of clients’ previous loans with Home Credit.
`POS_CASH_balance.csv`: Status of Point-of-Sale loans.
`installments_payments.csv`: Historical payment data for previous loans.
`credit_card_balance.csv`: Monthly credit card usage.

