
### Model Performance Summary

Several machine learning models were evaluated to predict breast cancer patient outcomes. Below is a summary of their performance based on precision, recall, f1-score, and accuracy.

1. Logistic Regression (Model_LR)
Accuracy: 80%

Precision: 83% (Class 0), 76% (Class 1)

Recall: 77% (Class 0), 82% (Class 1)

F1-Score: 80%

Summary: Performs moderately well but has lower recall for Class 0, meaning it misses some cases.

2. Random Forest (Model_RF)
Accuracy: 97%

Precision: 95% (Class 0), 100% (Class 1)

Recall: 100% (Class 0), 95% (Class 1)

F1-Score: 97%

Summary: The best-performing model with high precision and recall, making it highly reliable for prediction.

3. Support Vector Classifier (Model_SVC)
Accuracy: 80%

Precision: 86% (Class 0), 73% (Class 1)

Recall: 76% (Class 0), 84% (Class 1)

F1-Score: 80%

Summary: Similar to Logistic Regression, but slightly better precision for Class 0.

4. XGBoost (Model_XGB)
Accuracy: 96%

Precision: 93% (Class 0), 100% (Class 1)

Recall: 100% (Class 0), 93% (Class 1)

F1-Score: 96%

Summary: High performance, comparable to Random Forest, with strong predictive power.

5. Gradient Boosting (Model_GBoosting)
Accuracy: 84%

Precision: 87% (Class 0), 80% (Class 1)

Recall: 82% (Class 0), 86% (Class 1)

F1-Score: 84%

Summary: Decent performance, better than Logistic Regression and SVC, but lower than RF and XGB.

Best Model Recommendation
Random Forest (Model_RF) and XGBoost (Model_XGB) performed the best, achieving 96-97% accuracy.

Both models have high precision and recall, making them reliable choices for prediction.

If interpretability is needed, Logistic Regression or Gradient Boosting can be considered.

XGBoost is preferred for its balance between efficiency and accuracy
