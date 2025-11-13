📊 Project Overview
This project analyzes customer marketing campaign data to build a machine learning model that predicts which customers are most likely to respond to marketing campaigns. The analysis includes comprehensive data preprocessing, feature engineering, and handling of class imbalance to optimize campaign targeting strategies.

🎯 Business Problem
Marketing campaigns are expensive, and targeting the wrong customers leads to wasted resources. This project helps businesses:

Identify customers most likely to respond to campaigns

Optimize marketing budget allocation

Improve campaign response rates

Understand customer behavior patterns

📁 Dataset
The dataset contains customer information including:

Demographics: Age, Education, Marital Status, Income

Customer Behavior: Purchase history, Web visits, Deal purchases

Campaign Responses: Response to 5 different marketing campaigns

Engagement Metrics: Recency, Days engaged with company

Original Features: 29 columns, 2240 rows

Data Preprocessing
✅ Handled missing values in Income column

✅ Removed constant columns (Z_CostContact, Z_Revenue)

✅ Created new features (day_engaged, Age from Year_Birth)

✅ Combined marital status categories ('Married' and 'Together')

✅ Removed outliers using IQR method for Income and Age

✅ Encoded categorical variables using Label Encoding

Machine Learning Pipeline
Train-Test Split: 70-30 split with stratification

Feature Scaling: StandardScaler (fitted only on training data)

Class Imbalance: Addressed through appropriate metrics and techniques
