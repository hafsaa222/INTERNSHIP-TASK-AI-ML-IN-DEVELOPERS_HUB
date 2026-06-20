# DevelopersHub Corporation — AI/ML Engineering Internship

**Intern Name:** HAFSA ATIF 
**Due Date:** 26th June, 2026
**Tasks Completed:** 3 of 6 (Task 1, Task 3, Task 6)

## Tools & Libraries Used
Python, Jupyter Notebook / Google Colab, pandas, numpy, matplotlib, seaborn, scikit-learn

---

## Task 1: Dataset Visualization
- **Objective:** Explore and visualize the Iris dataset to understand feature distributions and species separability.
- **Dataset:** Iris Dataset (loaded directly via `seaborn.load_dataset('iris')`)
- **Approach:** EDA, scatter plot, histograms, and box plots across the 4 flower measurements.
- **Key Finding:** Setosa is clearly separable from Versicolor and Virginica based on petal length and width, while the other two species overlap more.
- **Notebook:** `task1_dataset_visualization.ipynb`

## Task 3: Heart Disease Prediction
- **Objective:** Predict whether a patient is at risk of heart disease using health measurements.
- **Dataset:** UCI Heart Disease Dataset (303 patients) — loaded directly from a public CSV URL, no manual download required.
- **Model:** Logistic Regression (with standardized features)
- **Evaluation:** Accuracy, Confusion Matrix, ROC-AUC Score
- **Key Finding:** Chest pain type (`cp`) and maximum heart rate (`thalach`) are among the strongest predictors of heart disease risk.
- **Notebook:** `task3_heart_disease_prediction.ipynb`

## Task 6: House Price Prediction
- **Objective:** Predict house sale prices based on property features such as living area, quality rating, and year built.
- **Dataset:** Kaggle "House Prices — Advanced Regression Techniques" (Ames, Iowa) — loaded directly from a public CSV URL, no manual download required.
- **Model:** Gradient Boosting Regressor
- **Evaluation:** MAE, RMSE, R² Score
- **Key Finding:** `OverallQual` (quality rating) and `GrLivArea` (living area) are the strongest predictors of sale price.
- **Notebook:** `task6_house_price_prediction.ipynb`

---

## How to Run
1. Open any notebook in Google Colab or Jupyter Notebook.
2. Run all cells top to bottom (`Runtime → Run all` in Colab).
3. No dataset downloads needed — all data loads directly from public URLs in code.


```
