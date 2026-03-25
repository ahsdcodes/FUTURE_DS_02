# 📉 Customer Retention & Churn Analysis
**Future Interns – Data Science & Analytics | Task 2**


## 📌 Objective
Analyze customer subscription data to identify churn patterns, key retention drivers, and customer lifetime trends — and deliver actionable recommendations to reduce customer loss for a subscription-based business.


## 📁 Dataset
- **Source:** Telco Customer Churn Dataset (Kaggle)
- **Records:** 7,032 customers
- **Features:** Contract type, tenure, payment method, services, monthly charges


## 🛠️ Tools Used
- Python (pandas, matplotlib, seaborn)
- Kaggle Notebook


## 📈 Key Metrics

| Metric                       | Value.           |
|------------------------------|------------------|
| Total Customers              | 7,032            |
| Churned Customers            | 1,869            |
| Retained Customers           | 5,163            |
| Overall Churn Rate           | 26.6%            |
| Avg Tenure (Churned)         | 18.0 months      |
| Avg Tenure (Retained)        | 37.7 months      |
| Avg Monthly Charge (Churned) | $74.44           |
| Avg Monthly Charge (Retained)| $61.31           |
| Highest Churn Contract       | Month-to-month   |
| Highest Churn Payment Method | Electronic check |


## 🔍 Key Findings

### 1. Contract Type is the Strongest Churn Predictor
- Month-to-month customers churn at dramatically higher rates
- Annual and two-year contract holders are far more likely to stay

### 2. Early Tenure is the Danger Zone
- Most churn occurs within the first 12 months
- Customers who pass 24 months rarely leave
- Points to an onboarding and early value problem

### 3. High Monthly Charges Drive Churn
- Churned customers pay $13/month more on average than retained ones
- Fiber Optic internet users show elevated churn — likely cost-related

### 4. Payment Method Flags At-Risk Customers
- Electronic check users have the highest churn rate
- Auto-payment customers (bank transfer, credit card) are significantly more loyal

### 5. Add-On Services Are Retention Anchors
- Customers with Online Security, Tech Support, Online Backup, and Device Protection retain at higher rates
- More services = more switching costs = lower churn


## ✅ Recommendations
1. Offer discounts to convert month-to-month customers to annual contracts
2. Build a structured onboarding program with check-ins at months 1, 3, and 6
3. Introduce loyalty discounts for high-charge customers in their first year
4. Incentivize autopay enrollment with a small monthly discount
5. Bundle add-on services into onboarding packages with free trials to increase stickiness


## 🔗 Kaggle Notebook
[View Full Analysis & Code](https://www.kaggle.com/code/aqsqcoder/notebook12c4e6acde)


*Internship: Future Interns | Track: Data Science & Analytics | Task: FUTURE_DS_02*
