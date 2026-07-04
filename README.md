#  House Price Predictor — Linear Regression

## Overview
A Linear Regression model trained on the California Housing dataset 
to predict median house values. Built as Task 1 for my ML internship 
at Maincrafts Technology.

## Results
| Metric | Value |
|--------|-------|
| MAE | 0.5332 (~$53,320 avg error) |
| RMSE | 0.7456 (~$74,558) |
| R² Score | 0.5758 (57.6% variance explained) |

## Key Finding
Median Income (MedInc) is the strongest predictor of house price 
with a correlation of 0.69.

## Project Structure
| File | Description |
|------|-------------|
| `task1_ml_linear_regression.ipynb` | Main notebook with full code |
| `house_price_model.pkl` | Saved trained model |
| `eda_distributions.png` | Feature distribution plots |
| `eda_correlation.png` | Correlation heatmap |
| `pred_vs_actual.png` | Predicted vs Actual scatter plot |
| `residuals.png` | Residual analysis plot |

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Dataset
California Housing Dataset (built into scikit-learn) — 
20,640 rows, 8 features, 1990 US Census data.
