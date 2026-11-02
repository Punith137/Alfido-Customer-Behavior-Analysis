# Alfido Tech — Customer Behavior Analysis

## Submission contents
- `Alfido_Customer_Behavior_Analysis.ipynb` — reproducible Jupyter notebook with Python code.
- `Alfido_Customer_Behavior_Analysis_Report.pdf` — detailed analysis report.
- `Alfido_Task_Submission_Executive_Summary.pdf` — one-page executive summary with GitHub code link.
- `alfido_category_revenue.png` and `alfido_segments.png` — report visualizations.

## Dataset
Use `ecommerce_customer_data_large.csv` from the supplied ZIP as the primary dataset. The second CSV (`ecommerce_customer_data_custom_ratios.csv`) is kept separate and is not merged.

## Run the notebook
1. Open the notebook in Google Colab or Jupyter.
2. In Colab, run the data-loading cell and upload either the original `archive.zip` or `ecommerce_customer_data_large.csv` when prompted.
3. In local Jupyter, put `archive.zip` or `ecommerce_customer_data_large.csv` in the same folder as the notebook.
4. Run all cells from top to bottom.

Dependencies: pandas, numpy, matplotlib, seaborn, scikit-learn.

## Interpretation notes
- Each row is treated as a transaction because no distinct transaction ID is supplied.
- Missing `Returns` values are treated as unknown.
- The supplied `Churn` column is reported separately from analyst-defined inactivity bands.
- Inactivity is a re-engagement proxy, not confirmed churn.
- K-means segmentation is descriptive, not a predictive churn model.
