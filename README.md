# Data Analyst Intern - Take-Home Assignment

## Objective
Demonstrate data sourcing, cleaning, analysis, and insights from real-world retail data.

## Business Domain
Retail (online transactions) – ties to revenue, inventory, and customer behavior.

## Setup Instructions
1. Clone repo: `git clone https://github.com/YOURUSERNAME/data-analyst-intern-assignment.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run cleaning: `jupyter notebook notebooks/01_cleaning.ipynb` (generates `/cleaned_data/*.csv`)
4. Run analysis: `jupyter notebook notebooks/02_analysis.ipynb` (generates insights & plots in `/report/images/`)

## Files Overview
- **Raw Data:** `/raw_data/online_retail.xlsx` (or download from [UCI Link](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx))
- **Cleaning:** `notebooks/01_cleaning.ipynb` (handles nulls, duplicates, outliers; exports CSVs)
- **Analysis:** `notebooks/02_analysis.ipynb` (5 insights with code/visuals)
- **Reports:** 
  - `/report/dataset_selection.pdf` (domain, source, questions)
  - `/report/analysis_report.pdf` (5 insights, visuals, implications)
- **Optional Presentation:** Convert analysis summary to 5 slides (problem, data, top 3 insights, recommendations, next steps)

## Key Insights Summary
See `analysis_report.pdf` for full details (Pareto products, CLV by frequency, cancellations, seasonality, country margins).

## Tools Used
Python (Pandas/NumPy for cleaning; Matplotlib/Seaborn for visuals).

Timeline: Completed in 2 days.
