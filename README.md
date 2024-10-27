# Bulldozer Sale Price Prediction

## Project Overview

This project aims to predict the future sale price of bulldozers based on their characteristics and historical sales data. Utilizing machine learning algorithms, we analyze various features to estimate the auction price of bulldozers.

## Problem Definition

How accurately can we predict the future sale price of a bulldozer, given its characteristics and previous auction prices of similar models?

## Data Sources

The dataset for this project is sourced from the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/c/bluebook-for-bulldozers/data). The main datasets include:

1. **Train.csv**: The training set containing data until the end of 2011.
2. **Valid.csv**: The validation set containing data from January 1, 2012, to April 30, 2012.
3. **Test.csv**: The test set (released later) containing data from May 1, 2012, to November 2012.

## Evaluation Metric

The evaluation metric for this project is the **Root Mean Squared Log Error (RMSLE)** between the actual and predicted auction prices. The goal is to minimize this error.

For more details on the evaluation, visit: [Kaggle Evaluation Overview](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation).

## Features

A detailed data dictionary for the dataset can be found [here](https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing). Key features in the dataset include:

- **SalesID**: Unique identifier for each sale.
- **SalePrice**: The sale price of the bulldozer (target variable).
- **MachineID**: Unique identifier for each machine.
- **ModelID**: Identifier for the model of the bulldozer.
- **YearMade**: The year the machine was manufactured.
- **MachineHoursCurrentMeter**: Hours the machine has been used.
- **UsageBand**: Band that categorizes the machine’s usage.
- **saledate**: The date when the auction occurred.

## Installation

To get started with this project, you will need to have the following installed:

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`

