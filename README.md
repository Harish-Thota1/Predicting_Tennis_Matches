## Tennis Match Outcome Prediction on Betting Data

### Overview

This project focuses on predicting the outcomes of ATP tennis matches by employing advanced probabilistic models. By analyzing a rich dataset containing tennis match records from 2005 to 2018, various models were trained to predict match results for the year 2019. The project evaluates several predictive models, including:

- **Naive Model**: A simple baseline model based on basic assumptions.
- **Univariate Logistic Regression Model**: A model utilizing logistic regression on a single feature to predict match outcomes.
- **Elo-based Models**: Variations of the Elo rating system, including standard Elo, surface-specific adjustments, and enhancements incorporating the margin of victory (MOV).
- **Bookmakers Consensus Model (BCM)**: A benchmark model that leverages betting odds from multiple bookmakers to predict match outcomes.

### Dataset

- **Source**: The dataset is sourced from [tennis-data.co.uk](http://www.tennis-data.co.uk/alldata.php).
- **Description**: It includes detailed records of men's professional tennis matches, encompassing player rankings, match outcomes, court surfaces, and betting odds from 2005 to 2018. This dataset is used to train the predictive models, while the 2019 match data is reserved for validation purposes.

### Validation

The models are validated using three key metrics:

- **Accuracy**: Measures the percentage of correctly predicted outcomes.
- **Calibration**: Assesses how closely predicted probabilities align with actual outcomes.
- **Log-Loss**: Emphasizes penalties for confident but incorrect predictions, making it crucial for evaluating betting-related models.

The benchmark for comparison is the **Bookmakers Consensus Model (BCM)**, which aggregates betting odds to provide a consensus probability for match outcomes.

### Installation Instructions

To run this project and utilize the necessary Jupyter notebooks, you’ll need to install the `import_ipynb` package. This package enables the import of Jupyter notebooks as if they were regular Python modules.

Install the `import_ipynb` package with the following command:

```bash
pip install import_ipynb
