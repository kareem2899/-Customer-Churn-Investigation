📊 Customer Churn Investigation
📝 Project Overview

Customer churn is a critical challenge for telecom companies, as retaining customers is often more cost-effective than acquiring new ones.
This project investigates customer churn patterns using the Telco Customer Churn Dataset.

By analyzing customer demographics, subscription types, and service usage, we aim to uncover what differentiates churned customers from those who stay.
The insights gained will serve as a foundation for building future predictive models for churn prevention.

🎯 Objectives

Explore customer behavior and identify churn-related factors.

Analyze the impact of contract type, payment method, and tenure on churn.

Detect imbalances and missing values in the dataset.

Prepare data insights for future binary classification models.

📂 Dataset

Name: Telco Customer Churn Dataset

Source: Public dataset (commonly available on Kaggle and IBM sample data)

Target Variable: Churn (Yes/No)

📚 Learning Outcomes

By completing this project, you will gain experience in:

✅ Binary target analysis (churn vs non-churn).

✅ Creating pivot tables for categorical comparisons.

✅ Visualizing categorical distributions using stacked bar charts.

✅ Analyzing correlation between numerical variables.

✅ Understanding data imbalance and missing values.

🔑 Key Insights to Explore

Distribution of churn across contract types (Month-to-Month, One year, Two year).

Effect of payment method on churn (Electronic check, Credit card, etc.).

Relationship between tenure (time as a customer) and churn.

Detecting which services (e.g., Internet, Streaming, Phone) influence churn.

💡 Hints for Analysis

Parse categorical variables (Contract, PaymentMethod, InternetService) carefully.

Use stacked bar charts to compare churn ratios across categories.

Apply correlation heatmaps to evaluate numerical variables (e.g., tenure, MonthlyCharges, TotalCharges).

Normalize categorical comparisons with percentage-based plots.

📊 Example Visualizations

Stacked bar charts: Churn by Contract Type.

Heatmap: Correlation between tenure, monthly charges, and churn.

Boxplot: MonthlyCharges vs Churn.

Pie chart: Distribution of churn across payment methods.

🛠️ Tools & Libraries

Python 3.x

Pandas – Data cleaning and pivot tables.

Matplotlib & Seaborn – Data visualization.

NumPy – Numerical operations.

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/customer-churn-investigation.git
cd customer-churn-investigation


Install required libraries:

pip install pandas numpy matplotlib seaborn


Place the dataset (Telco-Customer-Churn.csv) in the project folder.

Run the analysis notebook or script:

jupyter notebook churn_investigation.ipynb


or

python churn_investigation.py

📌 Future Work

Build a predictive model using Logistic Regression or Random Forest.

Apply SMOTE or resampling techniques to handle imbalance.

Create a dashboard for real-time churn tracking.

📧 Contact

Developed by karim Mamdouh
For inquiries, feel free to reach out via kareem.mamdouhk42@gmail.com.
