# Emmanuel-Moemeke-Deliverable-AnalystLab-Africa-Week-4
Predictive model building using labeled datasets.

Predicting Housing Prices & Titanic Survival Using Machine Learning

Overview
This project covers the end to end building and evaluation of two supervised machine learning models. The goal was to move beyond exploratory analysis and build models capable of making accurate, real world predictions on two well known datasets.

Models Built
1. 🏠 Linear Regression 
Trained a Linear Regression model to predict residential property prices based on structural and amenity based features.
2. 🚢 Logistic Regression 
Built a Logistic Regression model to classify whether a passenger survived or did not survive based on demographic and ticket related features.

Key Results
Housing Price Model (Linear Regression)
Baseline RMSE: 1,755,959
Model RMSE: 765,948 (prediction error cut by more than half)
R² Score: 0.8839 (88.4% of price variation explained by the features)
No overfitting: training and testing scores closely aligned

Titanic Survival Model (Logistic Regression)
Baseline Accuracy: 61.66%
Model Accuracy: 80.45% (a 19% improvement over blind guessing)
Recall: 69.57% | F1-Score: 73.28%
No overfitting: training (80.34%) and testing (80.45%) nearly identical
Confusion Matrix: 144 correct classifications out of 179 test passengers

Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

Datasets
Housing: 545 property records with 13 features (area, bedrooms, bathrooms, AC, furnishing, location)
Titanic: 891 passenger records with survival status, class, age, fare, gender, and family size

Acknowledgement
This project was completed as part of my learning experience with AnalystLab Africa.
