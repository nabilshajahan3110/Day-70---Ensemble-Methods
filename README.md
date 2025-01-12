## Day-70---Ensemble-Methods
As part of a 75-day data analysis challenge, this work on Python covers Ensemble Methods

Ensemble methods are powerful techniques in machine learning that combine predictions from multiple models to improve performance, reduce variance, and minimize overfitting. Python libraries like **scikit-learn, XGBoost, LightGBM, and CatBoost** make implementing these techniques straightforward.

### 1. Bagging (Bootstrap Aggregating)

**Definition:** Bagging involves training multiple models (usually of the same type) on different subsets of the training data created by bootstrapping (sampling with replacement). The final prediction is obtained by aggregating (e.g., averaging or majority voting) the predictions of all models.

**Goal:** Reduce variance and prevent overfitting.

**Example Algorithm:** Random Forest.

### 2. Boosting

**Definition:** Boosting is a sequential process where each model corrects the errors of the previous one. It combines weak learners (models slightly better than random guessing) into a strong learner.

**Goal:** Reduce bias and improve accuracy.

**Example Algorithms:** AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost.

### 3. Stacking (Stacked Generalization)

**Definition:** Stacking combines predictions from multiple base models (which can be of different types) using a meta-model. The meta-model is trained on the predictions of the base models to make the final prediction.
**Goal:** Leverage the strengths of diverse models to improve performance.

### Use Cases

**Bagging:** Random Forest for image classification, medical diagnosis.

**Boosting:** XGBoost for Kaggle competitions, credit scoring, anomaly detection.

**Stacking:** Combining deep learning models with traditional algorithms for ensemble predictions.
