# Alfido Tech — Customer Behavior Analysis

## Submission contents
- `Alfido_Customer_Behavior_Analysis.ipynb` — reproducible Jupyter notebook.
- `Alfido_Customer_Behavior_Analysis_Report.pdf` — detailed analysis report.
- `Alfido_Task_Submission_Executive_Summary.pdf` — one-page executive summary.
- `alfido_*.png` — visualizations used in the report.

## Dataset
Use `ecommerce_customer_data_large.csv` from the supplied ZIP as the primary dataset. The second CSV (`ecommerce_customer_data_custom_ratios.csv`) is kept separate and is not merged.

## Run the notebook
1. Extract the supplied ZIP.
2. Open the notebook in Google Colab or Jupyter.
3. Upload `ecommerce_customer_data_large.csv` to the runtime or set `DATA_PATH` to its location.
4. Run all cells from top to bottom.

Dependencies: pandas, numpy, matplotlib, seaborn, scikit-learn.

## Interpretation notes
- Each row is treated as a transaction because no distinct transaction ID is supplied.
- Missing `Returns` values are treated as unknown.
- The supplied `Churn` column is reported separately from analyst-defined inactivity bands.
- Inactivity is a re-engagement proxy, not confirmed churn.
- K-means segmentation is descriptive, not a predictive churn model.

## Before submitting
1. Upload the notebook and README to a GitHub repository.
2. Set repository visibility to Public or ensure the evaluator has access.
3. Upload large dataset/assets to Google Drive and set access to “Anyone with the link — Viewer” if permitted.
4. Paste the GitHub and Drive URLs into the Alfido Tech Task Submission form, clearly labeling the task number.
