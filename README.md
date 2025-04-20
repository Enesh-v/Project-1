 Clinical Data Cleaning & Visualization with Python

A small end-to-end Python project that demonstrates clinical data cleaning and visualization techniques, built with minimal dependencies. This project simulates an SDTM-like structure and includes missing data handling, exploratory analysis, and interactive visuals — ideal for clinical programmers and data scientists.



- Cleans clinical trial data (Age, Visit Date, Lab Results, AE flags)
- Applies:
  - Missing value imputation (mean, median, forward fill)
  - Categorical default handling
- Generates:
  - Descriptive statistics
  - Interactive and static visualizations
- Exports cleaned dataset for downstream analysis

Visualizations Include

- Age distribution (Seaborn)
- AE flag count plot
- Lab result vs. age scatter plot (Plotly interactive)

Tech Stack

- Python 3.x
- `pandas`, `numpy`
- `seaborn`, `matplotlib`, `plotly`

Output

- `clean_clinical_data.csv` – exported clean dataset

 Future Ideas

- Extend with real SDTM/ADaM datasets
- Integrate with Power BI or Dash for dashboarding
- Add QC flagging logic using rule-based checks







