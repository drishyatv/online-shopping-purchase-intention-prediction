# Online-Shopping-Purchase-Intention-Prediction
With the rapid growth of e-commerce platforms, understanding and predicting customer purchasing behavior has become crucial for online businesses. Many visitors browse online shopping websites without making a purchase, leading to lost sales opportunities.

📊 Online Shopper Purchase Intention Prediction

👤 Name

Drishya T V

🏢 Organization

Entri Elevate – Data Science and Machine Learning

📌 Project Overview

This project predicts whether an online shopper will make a purchase or not based on their browsing behavior on an e-commerce website. Many users visit online 

shopping sites without buying anything, so predicting purchase intention helps improve sales and marketing strategies.

🎯 Objective

To build a machine learning model that predicts Revenue (Yes/No) using user session data.

📂 Dataset

Source: UCI Machine Learning Repository

Link: https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

Rows: 12,330

Columns: 18

Target: Revenue (purchase or not)

⚙️ Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

🧹 Data Preprocessing

Removed duplicates

Converted boolean values to integers

Label encoding for categorical features

Handled outliers using IQR method

Feature scaling using RobustScaler

Train-test split (80-20)

📊 Models Used

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

XGBoost

📈 Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

🏆 Results

Random Forest → Highest accuracy

Logistic Regression → Best recall for buyers

XGBoost → Balanced performance

👉 Dataset is imbalanced, so recall and F1-score are more important than accuracy.

📌 Conclusion

Logistic Regression and XGBoost performed better in identifying potential buyers. This project shows how user behavior can be used to predict purchase intention 

and improve business decisions.

