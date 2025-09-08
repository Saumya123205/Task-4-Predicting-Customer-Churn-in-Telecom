# 📌 Predicting Customer Churn in Telecom
<img width="320" height="400" alt="Infograpfic image for Task-4" src="https://github.com/user-attachments/assets/da8a7559-2a7c-4ef0-87a8-d171d56b2e69" />


## 📖 Project Overview

Customer churn (when customers stop using a company’s services) is one of the biggest challenges for the telecom industry. Acquiring new customers is expensive, while retaining existing customers is more profitable.

## In this project, I used the Telco Customer Churn dataset to:

### ✅ Explore customer behavior through Exploratory Data Analysis (EDA)

### ✅ Identify key factors that drive churn

### ✅ Build a machine learning model to predict churn

### ✅ Provide business recommendations to reduce churn

This project is designed to be easy to understand for anyone (beginners, recruiters, or business stakeholders) by combining data science techniques with practical business insights.

## 📂 Dataset

### ✅ The dataset used is Telco Customer Churn (WA_Fn-UseC_-Telco-Customer-Churn.csv).

### ✅ It contains 7,043 customer records with the following information:

### ✅ Demographics: Gender, Senior Citizen, Dependents

### ✅ Account Info: Tenure, Contract type, Payment method, Billing type

### ✅ Services: Internet service, Phone service, Streaming services, Security add-ons

### ✅ Financials: Monthly charges, Total charges

### ✅ Target Variable: Churn (Yes/No)

## 🛠️ Tools & Libraries Used

### ✅ Python – Core programming language

### ✅ Pandas & NumPy – Data cleaning and preprocessing

### ✅ Matplotlib & Seaborn – Data visualization (EDA)

### ✅ Scikit-learn – Machine learning (encoding, model building, evaluation)

### ✅ Jupyter Notebook – Development and analysis environment

## ⚙️ Project Workflow

### Data Preprocessing

#### ✅ Handled missing values (e.g., TotalCharges column)

#### ✅ Dropped irrelevant column: customerID

#### ✅ Encoded categorical variables (Label Encoding & One-Hot Encoding)

### Exploratory Data Analysis (EDA)

#### ✅ Churn Distribution → Imbalance between churned and non-churned customers

#### ✅ Monthly Charges vs Churn → Higher charges customers churn more

#### ✅ Contract Type vs Churn → Month-to-month contracts have maximum churn

#### ✅ Payment Method vs Churn → Electronic check users churn the most

#### ✅ Tenure vs Churn → New customers churn heavily; long-tenured customers are loyal

## 🤖 Model Building

### Data Splitting

#### ✅ The dataset was split into training and testing sets to evaluate model performance effectively.

#### ✅ Training set was used to train the models, while the testing set was used to validate unseen data.

### Model Selection

### Multiple classification models were applied to predict churn, including:

#### ✅ Logistic Regression

#### ✅ Random Forest

### Feature Encoding & Scaling

#### ✅ Categorical features were encoded using Label Encoding and One-Hot Encoding.

#### ✅ Numerical features were standardized/scaled where required to improve model performance.

### Model Evaluation

#### Models were evaluated using:

##### ✅ Accuracy → Overall correctness of predictions

##### ✅ Precision → How many predicted churns were actually churns

##### ✅ Recall (Sensitivity) → How many actual churns were correctly predicted

##### ✅ F1-Score → Balance between Precision and Recall

## Best Performing Model

#### ✅ Among the tested models, the one with the highest balance of Accuracy, Precision, Recall, and F1-score (Random Forest model after Hyper Parameter Tunning) was selected as the final churn prediction model.

#### ✅ This model can be used by telecom companies to identify high-risk customers and take proactive actions.

## 📊 Key Insights

### ✅ Monthly Charges & Churn

### ✅ Customers with higher monthly charges are more likely to churn.

### ✅ Contract Type Matters

### ✅ Month-to-month customers churn the most.

### ✅ One-year and two-year contracts retain customers better.

## Tenure is Critical

### ✅ New customers (0–12 months) churn the most.

### ✅ Customers with 3+ years tenure are highly loyal.

## Payment Method & Trust

### ✅ Customers paying via Electronic Check churn the most.

### ✅ Customers using Bank Transfer or Credit Card (automatic payments) churn the least.

## 💡 Business Recommendations

### Loyalty Programs

#### ✅ Offer rewards, discounts, or premium benefits to long-tenure customers.

### Flexible Pricing & Bundling

#### ✅ Provide discounted bundles for high-charge customers to reduce churn.

### Onboarding Support for New Customers

#### ✅ Focus on first 6 months with proactive support, tutorials, and offers.

### Encourage Long-Term Contracts

#### ✅ Provide promotions (reduced activation fee, free months, add-on services) for switching from monthly to yearly contracts.

### Improve Payment Experience

#### ✅ Incentivize automatic payments (cashback, discounts) to move customers away from electronic checks.

### Proactive Retention Strategy

#### ✅ Use the churn prediction model to identify high-risk customers and send personalized offers before they churn.

## 💼 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/saumyasuteshnu-behera-50a478209/)
