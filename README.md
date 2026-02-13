Credit Risk Prediction using Machine Learning

Business Case: Bank GoodCredit
Tool Used: Python (Jupyter Notebook)
Domain: Banking & Financial Risk Analytics

This project focuses on predicting customer credit risk using Machine Learning techniques to identify whether a loan applicant is likely to default based on anonymized customer data. The solution follows an end-to-end data science workflow including data extraction, preprocessing, feature analysis, model building, and performance evaluation aligned with real-world banking risk analytics practices.

The dataset used in this project belongs to Bank GoodCredit and consists of anonymized customer information. Due to data privacy policies, sensitive customer attributes are masked and represented as engineered features.

The project involves three datasets:

Customer Demographics Data – Contains anonymized demographic features along with the target variable
Customer Account Data – Includes historical account and payment information
Customer Enquiry Data – Captures customer enquiry behavior

In this analysis, the primary focus is on the Customer Demographics dataset, which includes features labeled from feature_1 to feature_79 along with the target variable Bad_label.

The data is stored in a MySQL database as specified in the business case document. The datasets were extracted using Python’s MySQL connector and loaded into Pandas DataFrames for further analysis. Extracted data was stored locally to ensure efficient processing and to avoid repeated database access while maintaining data integrity.

Models Used

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
XGBoost Classifier

Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, MySQL, Jupyter Notebook

Model Evaluation Metric

ROC-AUC Score was used as the primary evaluation metric to measure model performance and risk discrimination capability.

Project Outcome

Ensemble models such as Random Forest and XGBoost achieved higher ROC-AUC scores and demonstrated better performance in identifying credit default risk compared to traditional classification models.

This project demonstrates an end-to-end machine learning approach to credit risk prediction in the banking domain and highlights how data science supports informed decision-making in financial risk management.
