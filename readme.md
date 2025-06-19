# Cafe Rewards Offer

This repository demonstrates downloading the Cafe Rewards Offer dataset from Kaggle and loading it with PySpark on Databricks.

## Setup

1. Place your `kaggle.json` credentials file in the repository root. An example file is provided.
2. Run `notebooks/download_dataset.ipynb` in a Databricks environment.

The notebook downloads the dataset to the `dados` directory and then writes three Delta tables—`bronze.customers`, `bronze.offers`, and `bronze.transactions`—from the CSV files.
