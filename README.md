# Customer-Segmentation-and-Churn-Prediction-Model

This project explores the customer behavior and churn patterns within the Indian telecom sector using demographic and usage data from four major telecom partners: **Airtel, Reliance Jio, Vodafone, and BSNL**.

##  Project Objective

To develop a robust classification model that:
- Segments customers based on demographics and usage patterns.
- Predicts customer churn using machine learning techniques.
- Helps telecom companies identify high-risk customers and improve retention strategies.

##  Datasets Used

1. **telecom_demographics.csv**  
   Contains customer demographic details:  
   - Age, gender, location (state, city, pincode)  
   - Number of dependents, estimated salary  
   - Registration date, telecom partner

2. **telecom_usage.csv**  
   Contains customer behavioral data:  
   - Calls made, SMS sent, data used  
   - `churn` (target variable: 1 = churned, 0 = retained)

##  Methodology

### 1. **Data Cleaning & Integration**
- Merged demographic and usage datasets using `customer_id`.
- Handled missing values and encoded categorical variables.
- Converted registration dates and engineered new features (e.g., time since registration, total interactions).

### 2. **Exploratory Data Analysis (EDA)**
- Visualized churn distribution across:
  - Telecom partners
  - States and cities
  - Usage behaviors (calls, SMS, data)
- Analyzed demographic influence on churn (e.g., age groups, salary brackets).

### 3. **Feature Engineering & Selection**
- Created derived features for segmentation (e.g., total usage).
- Applied correlation analysis and feature importance ranking.

### 4. **Model Building**
- Developed classification models:
  - **Logistic Regression**
  - **Random Forest**
 
- Evaluated models using:
  - Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Tuned hyperparameters and selected optimal features for final model.

### 5. **Customer Segmentation**
- Segmented users based on usage and demographic clusters.
- Identified high-value and high-risk customer groups.

##  Tools & Technologies

- **Python**: Data preprocessing, modeling (Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- **Excel**: Data review, cleaning, dashboard prototyping

## 📊 Key Insights

- Churn was significantly influenced by:
  - Lower data usage
  - Specific telecom partners
  - Demographic features such as age and income
- Retention strategies can be customized based on city, partner, or usage clusters.


