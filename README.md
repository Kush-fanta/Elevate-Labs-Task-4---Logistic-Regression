# Elevate-Labs-Task-4---Logistic-Regression

1. **Data Cleaning**
   - Removed unnecessary columns like `id` and unnamed columns.
   - Handled missing values (if any).

2. **Data Preprocessing**
   - Label encoded the target column (`diagnosis`).
   - Standardized features using Z-score normalization (`StandardScaler`).

3. **Model Building**
   - Split the dataset into **train** and **test** sets.
   - Trained a `LogisticRegression` model from `sklearn`.

4. **Evaluation**
   - Evaluated performance using:
     - **Confusion Matrix**
     - **Precision, Recall, F1-score**
     - **ROC-AUC Score**
     - **ROC Curve Visualization**

5. **Threshold Tuning**
   - Explored different probability thresholds for classification.
   - Explained how the **sigmoid function** maps predictions to probability values.

