# Disease_Prediction_For-Medicel_Data
Built a complete end-to-end classification pipeline in Python (Jupyter Notebook) to predict the likelihood of Heart Disease, Diabetes, and Breast Cancer using real-world UCI datasets.

# What I built:
• Trained & compared 4 classifiers: Logistic Regression, SVM, Random Forest, and XGBoost
• Applied full preprocessing: zero-value imputation, median fill, feature scaling
• Evaluated with Accuracy, ROC-AUC, Confusion Matrices & 5-fold Cross Validation
• Visualised Feature Importance, ROC Curves, and Correlation Heatmaps

# Key Results:
• XGBoost consistently delivered the highest AUC across all 3 datasets
• Glucose & BMI were top predictors for Diabetes
• Chest pain type & max heart rate dominated Heart Disease prediction
• SVM excelled on the high-dimensional Breast Cancer dataset

Key Takeaway: Proper data preprocessing (handling zero values, scaling) made a significant difference in model performance — often more than algorithm choice alone.

Tech Stack: Python · scikit-learn · XGBoost · Pandas · Matplotlib · Seaborn
