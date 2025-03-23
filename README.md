# Creditworthiness-Prediction-for-Credit-Card-Approval

📈 Project Overview

Development a model capable of estimating the creditworthiness of customers. 
This model will assist the dedicated team in deciding whether to approve or reject credit card applications.

🌐 Project Objective

The goal is to create a machine learning model that predicts the target variable TARGET, which indicates whether a customer has good creditworthiness (i.e., consistently pays their installments on time).

🔄 Value Proposition for Pro National Bank:

Improved risk assessment for credit card approvals.

Optimized decision-making by focusing on high-creditworthy customers.

Reduced financial risks by minimizing default rates through data-driven predictions.

📂 Dataset

The dataset contains anonymized information about customers who have applied for a credit line.

Key Features:

ID: Unique customer identifier.

CODE_GENDER: Customer's gender.

FLAGOWNCAR: Indicator of car ownership.

FLAGOWNREALTY: Indicator of homeownership.

CNT_CHILDREN: Number of children.

AMTINCOMETOTAL: Annual income.

NAMEINCOMETYPE: Type of income.

NAMEEDUCATIONTYPE: Education level.

NAMEFAMILYSTATUS: Marital status.

NAMEHOUSINGTYPE: Type of housing.

DAYS_BIRTH: Number of days since birth.

DAYS_EMPLOYED: Number of days employed (if positive, indicates unemployment duration).

FLAG_MOBIL: Indicator of having a mobile phone.

FLAGWORKPHONE: Indicator of having a work phone.

FLAG_PHONE: Indicator of having any phone.

FLAG_EMAIL: Indicator of having an email address.

OCCUPATION_TYPE: Type of occupation.

CNTFAMMEMBERS: Number of family members.

TARGET: 1 if the customer has high creditworthiness (consistently pays installments), 0 otherwise.

🎯 Key Activities

1️⃣ Exploratory Data Analysis (EDA)

Understanding the dataset's distribution and key patterns is essential. This involves:

Analyzing the TARGET distribution to detect class imbalances.

Investigating key factors like income, employment duration, and financial indicators affecting creditworthiness.

✅ Added Value: Identifying crucial patterns that impact predictive success.

2️⃣ Handling Class Imbalance

The TARGET variable may be imbalanced, with significantly more customers having good creditworthiness than those who do not. To address this, we apply:

Class Weights: Adjusting for imbalance in model training.

Oversampling or Undersampling: Modifying the dataset to ensure fair learning.

✅ Added Value: Enhances the model’s ability to detect potential defaulters effectively.

3️⃣ Model Development & Evaluation

Comparing multiple machine learning models:

Logistic Regression

Random Forest

XGBoost

Despite expectations of logistic regression performing poorly, other models like Random Forest and XGBoost also showed low precision and recall on the positive class in initial testing. The solution is to:

Tune hyperparameters.

Use appropriate evaluation metrics (e.g., ROC-AUC).

Optimize the model based on cross-validation performance.

✅ Added Value: Helps the bank make data-driven credit approval decisions, minimizing risks and improving customer trust.
