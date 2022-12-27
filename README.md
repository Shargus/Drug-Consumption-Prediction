# Drug Consumption Prediction
Analysis of machine learning techniques to predict drug consumption from personality traits.

Final project for the Mathematics in Machine Learning exam

Drug consumption dataset: http://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29

After an exploratory data analysis (EDA) of the dataset, some **data cleaning** and **data preprocessing** steps are performed (feature selection based on correlation analysis, missing/invalid values insertion, feature encoding, standardization, PCA, random undersampling/oversampling, SMOTE).

Four classification models are trained (**random forest**, **K-nearest neighbors**, **support vector machines**, **logistic regression**), with hyperparameters optimized through **grid search** via **K-fold cross-validation**.

The best classification pipeline (standardization + random oversampling + SVM) achieves a **sensitivity** of **0.817** and a **specificity** of **0.766**

## User guide
- * **Drug consumption prediction.ipynb**: code for the project (with visualizations and performance evaluation)
- * **Report.pdf**: report for the project (\w results)
