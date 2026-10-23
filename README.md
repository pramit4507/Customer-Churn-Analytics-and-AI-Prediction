# Customer Churn Prediction & Retention Analytics using AI

---

## 📌 Project Overview
In the competitive telecommunications sector, retaining existing customers is significantly more cost-effective than acquiring new ones. This project presents an end-to-end Machine Learning and AI-driven predictive analytics framework designed to analyze subscriber behavioral patterns, predict customer attrition risk (churn), and deliver actionable retention strategies.

This project is submitted as part of the **AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026** in collaboration with **BharatCares**.

---

## 📂 Repository Structure
```text
├── YourName_ProjectName.ipynb              # Jupyter Notebook containing full ML pipeline & EDA
├── YourName_ProjectName.py                 # Standalone Python executable script
├── requirements.txt                         # Python package dependencies
├── YourName_ProjectReport.docx             # Complete project report & documentation
├── Telco_Customer_Churn_Dataset.csv         # Project dataset
└── README.md                                # Project summary & guide

🔗 Dataset Information

Dataset Name: IBM Telco Customer Churn Dataset

Dataset Link: Kaggle - Telco Customer Churn

Dataset Description: Contains 7,043 customer records with 21 attributes covering:

Demographics: gender, SeniorCitizen, Partner, Dependents

Account Details: tenure, Contract, PaperlessBilling, PaymentMethod

Services Subscribed: PhoneService, MultipleLines, InternetService, OnlineSecurity, TechSupport

Financial Metrics: MonthlyCharges, TotalCharges

Target Column: Churn (Yes / No)

🛠️ Technologies Used

Language: Python 3.8+

Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Machine Learning: scikit-learn (StandardScaler, LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, GridSearchCV)

File Formats: Jupyter Notebook (.ipynb), CSV (.csv), Document (.docx), Markdown (.md)

⚙️ Setup & Execution Instructions

Clone or Download the Project Repository:

git clone <repository_url>
cd <repository_folder>


Install Required Dependencies:

pip install -r requirements.txt


Run the Analysis:

Open Jupyter Notebook or Jupyter Lab:

jupyter notebook


Open YourName_Customer_Churn_Analytics.ipynb and execute all cells sequentially (Cell > Run All).

📊 Key Insights & Model Results

Best Performing Model: Tuned Random Forest Classifier

Accuracy: ~80.2%

ROC-AUC Score: 0.845

Top 3 Drivers of Churn:

Contract Type: Month-to-month contracts exhibit significantly higher churn rates compared to 1- or 2-year contracts.

Tenure Length: High churn probability concentrated within the first 12 months of customer subscription.

Monthly Charges: Higher monthly charges correlate directly with an increased risk of churn, especially when unsupported by add-on services like TechSupport or OnlineSecurity.
