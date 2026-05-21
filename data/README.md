# Data

This project uses the Kaggle Netflix Customer Churn Dataset.

- Source: [Kaggle - Netflix Customer Churn Dataset](https://www.kaggle.com/datasets/abdulwadood11220/netflix-customer-churn-dataset?resource=download)
- Raw data path: `data/raw/netflix_customer_churn.csv`
- Processed data path: `data/processed/netflix_churn_cleaned.csv`

`notebooks/01_data_cleaning.ipynb` reads the raw CSV and writes the processed CSV used by the EDA, modeling, and business insights notebooks.

If replacing this with private or proprietary customer data, do not commit the data files to GitHub. Use sample data or document how to obtain the dataset instead.
