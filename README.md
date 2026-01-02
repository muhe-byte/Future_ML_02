# Future_ML_02

# Customer Churn Prediction System 🚀

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)

## 📌 Project Overview
In industries like Telecom and Banking, retaining existing customers is significantly more cost-effective than acquiring new ones. This project focuses on building an **End-to-End Machine Learning System** that identifies "at-risk" customers likely to cancel their service (Churn).

By analyzing historical customer behavior, service usage, and contract details, the system provides a **Churn Probability Score**, allowing the marketing team to take proactive retention actions.

---

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn.
- **Tools:** Jupyter Notebook, Power BI (Visual Dashboard).

---

## 📊 The Dataset
I utilized the **Telco Customer Churn Dataset**, which includes:
- **Demographics:** Gender, senior citizenship, partners, and dependents.
- **Services:** Phone, multiple lines, internet (Fiber optic/DSL), online security, streaming TV, etc.
- **Account Info:** Tenure, contract type, payment method, paperless billing, monthly charges, and total charges.
- **Target Variable:** `Churn` (Yes/No).

---

## ⚙️ Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Identified that **Month-to-Month** contract holders have the highest churn rate.
- Discovered a strong correlation between **Fiber Optic** users and churn due to higher pricing.
- Analyzed class imbalance (Churned vs. Retained).



### 2. Feature Engineering & Preprocessing
- Converted categorical strings into numerical values using **One-Hot Encoding**.
- Handled missing values in `TotalCharges`.
- Scaled numerical features for better model performance.

### 3. Machine Learning Modeling
Tested multiple classification algorithms to find the best performance:
- **Logistic Regression** (Baseline)
- **Random Forest** (High interpretability)
- **XGBoost** (Optimized Gradient Boosting) - *Best Performer*

### 4. Evaluation Metrics
Focused on more than just accuracy to handle class imbalance:
- **Precision & Recall:** To minimize missing actual churners.
- **Confusion Matrix:** To visualize True Positives vs. False Positives.
- **ROC-AUC Score:** Evaluated the model's ability to distinguish between classes.



---

## 📈 Business Insights & Dashboard
The final output is an interactive **Power BI Dashboard** designed for stakeholders:
- **Top Churn Drivers:** Visualizing why people leave (e.g., Electronic Check payments).
- **At-Risk Segments:** Identifying high-probability churners for immediate outreach.
- **Revenue Impact:** Calculating the potential loss from predicted churners.

---

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/muhe-byte/churn-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook churn_analysis.ipynb`

---

## 👤 Author
**[Muhamed Nuru]**
*Data Science Intern*
[www.linkedin.com/in/muhamed-nuru] |
