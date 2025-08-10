# Breast Cancer Prediction using Logistic Regression (L1 Reguralisation)🧬

## Project Overview
This project aims to predict breast cancer diagnosis using a Logistic Regression model. The focus was on building a robust, well-regularized model to avoid overfitting and improve generalization.

---

## Data Preprocessing ✨
- **Duplicate & Null Value Removal:** Cleaned the dataset by removing duplicate entries and handling missing values.
- **Outlier Detection & Cross-Validation:**  
  Tested multiple outlier detection methods including Box Plot, Z-Score, and Cook's Distance.  
  Selected the method that resulted in the least accuracy because higher accuracy indicated model overfitting.  
- **Feature Selection with RFE:**  
  Applied Recursive Feature Elimination (RFE) to remove unnecessary and highly correlated features, improving model simplicity and performance.

---

## Model Training & Evaluation 🧠
- **Regularization:**  
  Used L1 regularization (Lasso) to reduce overfitting and enhance model robustness.

---

## Experiment Tracking with MLflow 🚀

The entire machine learning workflow is tracked using **MLflow** for better reproducibility and experiment management. This includes:  
- Logging parameters, metrics, and artifacts  
- Comparing different model runs and tuning experiments  
- Ensuring a clear audit trail of model development steps  

Using MLflow has helped maintain transparency and efficiency throughout the model building process.

---

## Performance Metrics 📊

| Metric       | Class 0 (Benign) | Class 1 (Malignant) | Overall          |
|--------------|------------------|---------------------|------------------|
| Precision    | 0.88             | 1.00                |                  |
| Recall       | 1.00             | 0.81                |                  |
| F1-Score     | 0.94             | 0.89                |                  |
| Support      | 67               | 47                  | 114 (Total)      |
| **Accuracy** |                  |                     | **0.92**         |
| Macro Avg.   | 0.94             | 0.90                | 0.92 (avg)       |
| Weighted Avg.| 0.93             | 0.92                | 0.92 (avg)       |

---

Thank you for checking out this project! Feel free to open issues or contribute. 🙌
