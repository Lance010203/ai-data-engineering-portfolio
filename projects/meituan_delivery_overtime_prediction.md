# Meituan Delivery Overtime Prediction

## Project Overview

This project focuses on identifying high-risk overtime orders in an instant delivery scenario. Based on anonymized order-level delivery data, the project involved data cleaning, feature engineering, binary classification modeling, and model evaluation.

## Data Processing

The cleaned dataset contained approximately 568,000 valid samples. The original data included order creation, dispatch, acceptance, pickup, delivery, and distance-related fields.

Main data processing tasks included:

- Handling missing values and duplicate records
- Converting time fields into consistent datetime formats
- Checking abnormal delivery durations and distance values
- Constructing time-difference features
- Preparing a clean dataset for model training

## Feature Engineering

Key features included:

- Dispatch delay
- Rider response time
- Pickup waiting time
- Delivery duration
- Merchant-user distance
- Courier-merchant distance
- Time-related features

## Modeling

XGBoost was used as the main binary classification model to identify potential overtime orders.

## Evaluation

The model was evaluated using:

- AUC
- Precision
- Recall
- F1-score
- Confusion matrix

## Notes

Due to data privacy restrictions, the original dataset is not uploaded. This repository only presents the project workflow and summarized methodology.
