# Tennis Match Outcome Prediction on Betting Data

## Overview

This project focuses on predicting the outcomes of ATP tennis matches using advanced probabilistic models. By analyzing a dataset containing tennis match records from 2005 to 2018, various models are trained to predict match results for the year 2019. The project includes the evaluation of several models such as the Naive model, Univariate Logistic Regression model, Elo-based models, and the Bookmakers Consensus Model (BCM), with special attention to surface-specific adjustments for better accuracy.

## Dataset

- **Source**: The dataset for this project is sourced from [tennis-data.co.uk](http://www.tennis-data.co.uk/alldata.php).
- **Description**: The dataset includes detailed records of men’s professional tennis matches, including player rankings, match outcomes, court surfaces, and betting odds from 2005 to 2018. This dataset is used to train predictive models, with 2019 data used for validation.

## Validation

Models are validated using three key metrics: accuracy, calibration, and log-loss. These metrics are used to assess the performance of each model, with comparisons made against a benchmark model, the Bookmakers Consensus Model (BCM). The goal is to identify the models that provide the most reliable and accurate predictions for tennis match outcomes.

## Installation Instructions

To run the project and use the necessary notebooks, you'll need to install the `import_ipynb` package. This package allows for the seamless import of Jupyter notebooks as if they were regular Python modules.

Install `import_ipynb` with the following command:

```bash
pip install import_ipynb

