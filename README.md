# Sales Prediction - Machine Learning Project

## Overview
A machine learning project that predicts sales based on advertising spend across multiple channels (TV, Radio, Newspaper). This project analyzes which advertising channels have the strongest impact on sales and builds predictive models.

## Dataset
- **File:** `Advertising.csv`
- **Records:** 200 observations
- **Features:** TV, Radio, Newspaper (advertising spend in thousands of dollars)
- **Target:** Sales (in thousands of dollars)
- **Source:** Advertising Sales Dataset

## Project Structure
CodeAlpha_SalesPrediction/
├── sales_prediction.py          # Main analysis script
├── Advertising.csv              # Input dataset
├── 01_sales_exploration.png     # EDA visualizations
├── 02_sales_correlation.png     # Correlation heatmap
├── 03_sales_predictions_comparison.png  # Model predictions
└── 04_sales_feature_importance.png      # Feature importance

## Features
- **Exploratory Data Analysis (EDA):** Distribution plots, scatter plots with trend lines
- **Correlation Analysis:** Heatmap showing relationships between variables
- **Feature Engineering:** 
  - TV-Radio interaction
  - TV-Newspaper interaction
  - Radio-Newspaper interaction
  - Total advertising spend
- **Model Comparison:**
  - Linear Regression (Baseline)
  - Random Forest Regressor
  - Gradient Boosting Regressor
- **Performance Metrics:** R² Score, MAE (Mean Absolute Error), RMSE

## Key Findings
- **TV Advertising:** Strongest correlation with sales (0.78) - Most impactful channel
- **Radio Advertising:** Moderate impact (0.58) - Secondary channel
- **Newspaper Advertising:** Weak predictor (0.23) - Limited direct impact
- **Best Model:** Random Forest with R² = 0.87 (explains 87% of sales variance)
- **Prediction Accuracy:** ±2000-3000 dollars on average

## How to Run
```bash
# Navigate to project folder
cd CodeAlpha_SalesPrediction

# Install dependencies (if needed)
pip install pandas numpy matplotlib seaborn scikit-learn

# Run analysis
python sales_prediction.py
```

## Output
The script generates:
1. **Console Output:** Model accuracies, feature importance, business insights
2. **4 PNG Files:** Visualizations for analysis and presentation
3. **Processing Time:** ~2-3 minutes

## Technologies Used
- **Python(jupyter notebook)**
- **Pandas:** Data manipulation and analysis
- **Numpy:** Numerical computations
- **Scikit-learn:** Machine learning models (Linear Regression, Random Forest, Gradient Boosting)
- **Matplotlib & Seaborn:** Data visualization

## Business Insights
- TV advertising is the primary driver of sales
- Multi-channel campaigns show synergistic effects
- Model can predict sales within ±2000-3000 dollars
- Useful for budgeting and campaign optimization

## Author
ALQAMA NAJAM - Data Science Intern at CodeAlpha

## Date
2026
