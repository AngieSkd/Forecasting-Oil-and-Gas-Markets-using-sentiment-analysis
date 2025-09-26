# Demo Repository – Data Management & Forecasting Example

This repository contains a **demonstration of data management, compilation, and forecasting workflows** in Python, based on a cleaned version of a Master’s dissertation project.

⚠️ **Note:** All data included here are **synthetic** and generated solely for demonstration purposes.  
No licensed or confidential data are included.

## Contents
- `Dissertation_demo.ipynb` — main Jupyter notebook (cleaned version).  
- `example_data/` — synthetic datasets used in the notebook.  
  - `synthetic_prices.csv`  
  - `synthetic_headlines.csv`  
  - `synthetic_weekly_returns.csv`  
  - `synthetic_weekly_sentiment.csv`  

## How to use
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib scikit-learn statsmodels xgboost
   ```
2. Open the notebook:  
   ```bash
   jupyter notebook Dissertation_demo.ipynb
   ```

The notebook demonstrates:
- Loading daily synthetic prices and headlines  
- Resampling prices to weekly frequency (week ending Friday)  
- Aligning daily headlines with weekly data  
- Aggregating sentiment and compiling datasets  
- Feature engineering and basic forecasting  
- Visualising results  

---
This demo is intended to showcase programming skills in **data management, compilation, and visualisation** using Python.
