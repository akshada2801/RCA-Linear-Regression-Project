# RCA Project: Linear Regression Analysis

## Project Title
Implementation and Analysis of Linear Regression Using Python

## Aim
Implement Simple and Multiple Linear Regression using the California Housing dataset, visualize the data, predict continuous target values, and evaluate model performance.

## Dataset
California Housing dataset loaded through `sklearn.datasets.fetch_california_housing`. The target `MedHouseVal` is in units of $100,000.

## Tools
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project workflow
1. Import libraries
2. Load and inspect dataset
3. Check missing values and duplicates
4. Exploratory data analysis and visualization
5. Simple Linear Regression (Median Income → Median House Value)
6. Multiple Linear Regression (all eight features → Median House Value)
7. Evaluate with MAE, MSE, RMSE and R²
8. Compare models
9. Actual vs predicted and residual plots
10. Predict a sample and export CSV files

## Run
Open the notebook in Google Colab and select **Runtime → Run all**. The dataset is fetched by scikit-learn, so an internet connection may be required the first time.

## Output CSV files
- `california_housing_dataset.csv`
- `actual_vs_predicted.csv`
- `model_evaluation_results.csv`

## Note
This is an educational regression exercise. The California Housing dataset contains aggregated area-level records, not individual home listings, and its target is capped.
