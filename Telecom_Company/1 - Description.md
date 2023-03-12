# Description - Telecommunications company customer churn

This project uses Scikit-Learn and XGBoost to predict customer churn for a hypothetical telecommunications company from Kaggle. 

As the data was very unbalanced, it was necessary to use SKLearn's Synthetic Minority Oversampling Technique (SMOTE) to artificially balancing. As SMOTE only accepts numerical data, all cathegorical data was translated into numerical by the SKLearn tool LabelEncoder.

With cleanned and prepared data, K-Nearest Neighbors, Decision Tree Classifier, Support Vector Machine, Random Forest and XGBoost algorithms were applied and compared to a DummyClassifier.
