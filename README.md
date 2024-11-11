
# ETL Project: Shopping Behavior Data Analysis

## Project Overview

This project performs a complete ETL (Extract, Transform, Load) process on two consumer shopping behavior datasets. The datasets contain information about customer demographics, purchase history, product details, and payment methods. The goal is to clean, transform, and merge these datasets for comprehensive analysis.

## Steps Involved

1. **Extract**: Loaded the data from two CSV files (`shopping_behavior_updated.csv` and `shopping_trends.csv`).
2. **Transform**:
   - Cleaned the data by standardizing column names and handling missing values.
   - Merged the datasets on `customer_id`.
   - Created new features such as `total_purchase_amount` and encoded categorical variables.
3. **Load**: Saved the cleaned and transformed dataset to a new CSV file (`cleaned_shopping_data.csv`).

## How to Run

1. Ensure you have the necessary Python packages installed:
   ```bash
   pip install pandas
   ```
2. Place the data files (`shopping_behavior_updated.csv` and `shopping_trends.csv`) in the same directory as the Jupyter Notebook.
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook etl_shopping_behavior_analysis.ipynb
   ```
4. Run all cells to execute the ETL process.

## Conclusion

This project demonstrates a full ETL workflow on consumer shopping data, providing a clean and integrated dataset ready for further analysis and visualization.
