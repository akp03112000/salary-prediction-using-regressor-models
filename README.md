# 💼 Salary Prediction Using Decision Tree & Random Forest Regressors

This project uses supervised machine learning techniques to predict salary based on years of experience. It includes exploratory data analysis, model training using **Decision Tree Regressor** and **Random Forest Regressor**, and performance evaluation. The project demonstrates the practical use of regression algorithms and highlights the importance of model interpretability and accuracy.

---

## Dataset

- Size: ~30 entries
- Features:
  - YearsExperience
  - Salary
- Target: Salary (continuous value)
- Source: Self-generated / Kaggle
- Format: CSV file

---

## Models Used

- Decision Tree Regressor
- Random Forest Regressor

---

## Workflow

1. Data Import & Cleaning
2. Exploratory Data Analysis (EDA)
3. Model Building
4. Model Evaluation (MAE, MSE, RMSE, R² Score)
5. Visualizations & Results Interpretation

---

## Evaluation Metrics

| Model              | MAE   | MSE   | RMSE  | R² Score |
|-------------------|-------|-------|-------|----------|
| Decision Tree      | 0.22  | 0.12  | 0.35  | 0.88     |
| Random Forest      | 0.11  | 0.05  | 0.23  | 0.95     |

Random Forest performs better due to ensemble learning, offering more accurate and stable predictions compared to a single Decision Tree.

---

## Technologies

- Python 3.10.7
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## Visual Outputs

- Scatter Plots
- Model Fit Visualization
- Predicted vs Actual Salary Graph
- Error Metrics Plot

---

## Future Scope

- Add more features like job title, industry, education
- Use polynomial regression or XGBoost
- Add GUI or Flask API for real-time predictions

---

## Report

The final report is included in the /report directory:
- Salary Analysis Report by Akhilesh.pdf

---
