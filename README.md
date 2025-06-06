# Housing Price Prediction Using Regression Models

A machine learning project developed for the CST3070 Artificial Intelligence 2024–25 module.

## Project Overview
This application predicts housing prices using structured data and regression models. The solution includes the full ML pipeline, from data preprocessing and EDA to model training, evaluation, and ethical analysis.

## Features and Marking Criteria Coverage

### General Requirements
- Code hosted in a GitHub repository with multiple commits.
- Dataset sourced from a public repository (e.g., Kaggle/UCI).
- All data files and notebooks included.

## Dataset
The dataset used is the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) from Kaggle. It contains 79 explanatory variables describing residential homes in Ames, Iowa.

- **Target variable**: `SalePrice`
- **Key features**: `OverallQual`, `GrLivArea`, `GarageCars`, `TotalBsmtSF`, `YearBuilt`, etc.

## Data Preprocessing & EDA
- Handled missing values and introduced artificial noise for cleaning demonstration.
- Normalized numeric features and encoded categorical ones.
- Feature engineering included transformations like total square footage and age of property.
- EDA conducted with histograms, boxplots, and correlation heatmaps to reveal patterns and trends.

## Model Performance
Multiple regression models were trained and evaluated:

- **Linear Regression**: R² = 0.84  
- **Decision Tree Regressor**: R² = 0.79  
- **(Optional) Random Forest Regressor**: R² = 0.89

Performance was measured using R², MAE, and RMSE. Visualizations of predictions vs. actual values included.

## Ethical Considerations
- **Bias Identification**: Location and construction year features showed potential socioeconomic bias.
- **Mitigation Strategies**: Outlier removal, fairness-aware feature selection, and ethical commentary included.

## Tech Stack
- Python
- scikit-learn, pandas, matplotlib, seaborn
- Jupyter Notebook

## How to Run
1. Clone the repository.
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Open `housing_model.ipynb` in Jupyter Notebook and run all cells.

## Notes
This project demonstrates an end-to-end machine learning workflow with ethical awareness and practical implementation. It fully meets the coursework criteria and is ready for submission or demonstration.
