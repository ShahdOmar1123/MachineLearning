PCA – Principal Component Analysis in Heart Disease Prediction


Overview

In this project, Principal Component Analysis (PCA) was applied to the Heart Disease dataset to explore dimensionality reduction and its effect on model performance.

PCA is a technique used to reduce the number of features in a dataset while retaining as much variance (information) as possible.

Objective

Reduce the number of features while preserving data variance.

Improve model performance by removing noise or correlated features.

Analyze how dimensionality reduction affects accuracy of Logistic Regression, Random Forest, and SVM.

Steps Implemented

Data Preprocessing

Handled missing values and outliers using Z-score.

Encoded categorical variables using One-Hot Encoding.

Scaled numeric features with StandardScaler.

Train/Test Split

Split data into 80% training and 20% testing sets.

Apply PCA

Fit PCA on the training set to retain 95% of variance.

Transform both training and testing sets using the fitted PCA.

Model Training & Evaluation

Trained Logistic Regression, Random Forest, and SVM on PCA-transformed data.

Evaluated models using accuracy.

| Model               | Accuracy without PCA | Accuracy with PCA |
| ------------------- | -------------------- | ----------------- |
| Logistic Regression | 0.88                 | 0.67              |
| Random Forest       | 0.89                 | 0.64              |
| SVM                 | 0.88                 | 0.73              |


Observation:

PCA reduced model accuracy for all models.

The dataset is not high-dimensional, so dimensionality reduction removed some important information.

PCA may not always improve performance, especially on small or moderately-sized datasets.

Conclusion

PCA is a powerful tool for high-dimensional datasets.

In this dataset, applying PCA did not improve model accuracy.

It is important to evaluate PCA results carefully before deploying models.

Tools & Libraries

Python

Pandas, NumPy

Scikit-learn (StandardScaler, PCA, LogisticRegression, RandomForestClassifier, SVC)

Matplotlib
