# House Price Prediction Using Machine Learning

## Project Overview
This project focuses on predicting house prices using machine learning techniques. It uses housing data and applies different regression algorithms to compare model performance and identify the best-performing model.

## Dataset
- Dataset: California Housing Dataset
- Target Variable: Median House Value
- Features include location, population, income, and housing-related information.

## Machine Learning Models
1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. Hyperparameter-tuned Ridge Regression
5. Hyperparameter-tuned Lasso Regression

## Model Evaluation

The models were evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Best Model

**Best Ridge Regression**

| Metric | Score |
|---|---:|
| MAE | 50678.21 |
| RMSE | 70003.84 |
| R² Score | 0.6260 |

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

## Project Files
- `House_Price_Prediction.ipynb` – Complete project notebook
- `best_ridge_model.pkl` – Saved trained model
- `model_comparison.csv` – Model performance comparison
- `requirements.txt` – Required libraries

## Conclusion
The project compares five regression prediction results. Best Ridge Regression achieved the highest R² score of approximately 0.6260 among the evaluated results.

The project demonstrates data preprocessing, feature scaling, regression modelling, hyperparameter tuning, model evaluation, and model saving.
