# Bank-Credit-Card-Loan-Defaulter-Prediction
This project involves the analysis and prediction of credit loan defaults using machine learning techniques. It begins by loading and exploring two datasets: 'application_record.csv' containing applicant information and 'credit_record.csv' with credit history data. Data preprocessing includes creating a 'target' variable based on credit status, calculating applicant age and job experience, and handling missing values.
Column renaming and one-hot encoding are performed for feature engineering, followed by standard scaling to prepare the data for modeling. Duplicate rows are removed, and a heatmap is generated to visualize feature correlations. The dataset is split into training and testing sets.
Unsupervised anomaly detection methods, including Isolation Forest and One-Class SVM, are applied to the training data to identify potential credit defaults. The project aims to predict and mitigate credit risks efficiently, facilitating informed decision-making for loan approval. The code is well-documented and organized for clarity and reproducibility.
