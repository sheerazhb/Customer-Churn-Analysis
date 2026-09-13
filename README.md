# Customer Churn Prediction
## Week 1: Exploratory Data Analysis
### Dataset
- Source: Telco Customer Churn (Kaggle)
- Size: 7,043 customers, 21 features
- Target: Predict customer churn (Yes/No)

### Key Findings
- Overall Churn Rate: 26.54% of customers churned (1,869 out of 7,043).
- Tenure Risk Window: Median tenure for churned customers is ~10 months vs 38 months for retained customers.
- Contract Type: Month-to-month contracts have ~42.7% churn, while 2-year contracts drop to ~2.8%.
- Internet Service: Fiber optic subscribers churn at ~41.9%, compared to ~19.0% for DSL.
- Payment Method: Electronic check has the highest churn rate at ~45.3%.
- Data Cleaning: TotalCharges had 11 missing values from new accounts (tenure = 0), imputed with the median ($1,397.48).

### Setup
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook "Week 1 - Customer Churn EDA.ipynb"
