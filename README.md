E-Commerce Customer Churn Prediction 🛒📉
-----------------------------------------
📋 Project Overview
--------------------
This project aims to predict customer churn for an e-commerce platform. By identifying "at-risk" customers who are likely to stop using the service, the business can take proactive measures (special offers, improved support) to retain them.

🚀 Key Results
---------------
Accuracy: 94% — Overall correctness of the model.

Recall (Churn Class): 74% — The model successfully identifies 74% of all actual churners.

Key Drivers: Identified Tenure, Cashback Amount, and Warehouse-to-Home Distance as the most significant predictors of churn.

🛠️ Tech Stack
----------------
Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Model: Random Forest Classifier (Ensemble Learning)

🧬 Data Pipeline & Logic Layer
----------------------------------
1. Data Cleaning & Preprocessing
Handling Outliers: Used Winsorization (Capping) on features like WarehouseToHome to prevent extreme values from skewing the model.

Feature Encoding: Applied One-Hot Encoding to categorical variables such as Gender, MaritalStatus, and PreferredPaymentMode.

Train-Test Split: Segmented data into 80% Training and 20% Testing sets to ensure unbiased evaluation.

2. Model Building
Implemented a Random Forest Classifier with 100 Decision Trees.

Used Ensemble Learning logic to reduce variance and improve the stability of predictions.

3. Evaluation
Utilized Confusion Matrix and Classification Report to analyze performance.

Focused on Recall as the primary metric to minimize "False Negatives" (missing customers who actually churn).

📈 Business Insights
----------------------
New Customer Risk: Low Tenure is the strongest predictor of churn, suggesting a need for better onboarding in the first 3 months.

Logistics Impact: High Warehouse-to-Home distance correlates with churn, likely due to longer delivery times or higher shipping costs.

Incentive Sensitivity: Cashback is a major retention tool; customers are highly sensitive to reward fluctuations.

💻 How to Run
-----------------
1)Clone the repository.
2)Install requirements: pip install -r requirements.txt.
3)Run the Jupyter Notebook or Python script to see the training and evaluation results.

