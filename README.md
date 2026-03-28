End-to-End Machine Learning Pipeline for Automated Loan Evaluation


 Project Overview
This project features a robust Machine Learning pipeline designed to automate the loan approval process for financial institutions. By leveraging the K-Nearest Neighbors (KNN) algorithm, the system evaluates applicant data—including CIBIL scores, annual income, and asset valuations—to provide a provisional credit decision with high precision.

The system features an interactive Institutional Terminal that generates a professional Statutory Credit Evaluation Report, simulating real-world fintech software used by bank underwriters.

 Key Features
Automated Data Pre-processing: Handles categorical encoding (LabelEncoder) and numerical normalization (MinMaxScaler).

Predictive Modeling: Implemented a tuned KNN Classifier for similarity-based risk assessment.

Interactive Banking Terminal: Professional CLI for real-time credit evaluation.

Risk Metrics: Calculates key indicators like Debt-to-Income (DTI) Ratio and system confidence intervals.

Model Persistence: Serialized model export (.pkl) using Pickle for seamless deployment.




 Tech Stack
Language: Python

Data Analysis: Pandas, NumPy

Machine Learning: Scikit-Learn (KNN, LabelEncoder, MinMaxScaler)

Visualization: Seaborn, Matplotlib

Model Storage: Pickle (Serialization)



Dataset Features
The model evaluates 12 critical financial parameters:

Financials: Annual Gross Income, Loan Amount, Amortization Period (Term).

Credit History: CIBIL / Bureau Score.

Collateral: Residential, Commercial, Luxury, and Liquid Asset Valuations.

Demographics: Education Level and Employment Status.
