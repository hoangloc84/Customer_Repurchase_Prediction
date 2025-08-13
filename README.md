Customer Repurchase Prediction
This project uses machine learning to predict if a customer will make another purchase within the next 30 days based on their transaction history.

Process Overview
Data Cleaning: Raw transaction data is cleaned by removing canceled orders, invalid entries, and duplicates.

Feature Engineering: Customer behavior features are created, including RFM (Recency, Frequency, Monetary) metrics and customer clustering via K-Means.

Modeling: A Random Forest and a Logistic Regression model are trained and compared, using a data leakage-proof process.

Evaluation: Models are evaluated on their ability to predict returning customers, focusing on AUC-ROC, Recall, and F1-Score.

How to Run
Install dependencies:

pip install pandas numpy scikit-learn

Prepare data: Run the initial data cleaning script to generate cleaned_retail_data.csv.

Run analysis: Execute the main Python script or Jupyter Notebook (analysis.ipynb).

Conclusion
The Random Forest model is recommended. It achieved a superior Recall score of 0.62 and an AUC-ROC of 0.740, making it more effective at identifying potential returning customers for targeted marketing campaigns.
