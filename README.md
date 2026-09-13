# Company Acquisition Data Analysis

An exploratory data analysis of acquisitions made by major tech companies (Apple, Facebook, IBM, Twitter, Yahoo, Microsoft, Google) through 2015.

## Overview

This project cleans and explores a dataset of company acquisitions, examining distributions, correlations, and statistical relationships between acquisition year, value, and parent company.

## Approach

- **Data cleaning**: missing values handled via mean imputation and forward-fill
- **Encoding**: categorical fields converted to numeric using label encoding
- **Scaling**: standardization and normalization applied for comparison
- **Visualization**: histograms, box plots, bar charts, and QQ plots across all fields
- **Statistical analysis**: Pearson and Kendall correlation, plus hypothesis testing on acquisition year vs. value and acquisition year vs. parent company

## Key Findings

- Acquisition year and acquisition value show a weak positive correlation
- Acquisition year and parent company show a weak negative correlation (approximately -0.18, roughly 18% inverse dependence)

## Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, SciPy, Statsmodels)
- Jupyter Notebook

## Files

- `company_acquisition_analysis.ipynb` — full analysis notebook
- `acquisitions.csv` — dataset
- `presentation.pptx` — project presentation slides

## Running the Project

```bash
pip install pandas numpy scikit-learn matplotlib scipy statsmodels jupyter
jupyter notebook company_acquisition_analysis.ipynb
```

## Author

Aishwarya Ramanath Shanbhag
