Credit Risk Customers Dataset 💳

Dataset Overview 🔍
This dataset offers a comprehensive view of customers and their creditworthiness. It's a goldmine for building credit risk prediction models.

Source: Kaggle
Link: [https://www.kaggle.com/datasets/ppb00x/credit-risk-customers]
Format: Comma-separated values (CSV)


Data Exploration (EDA) 📊
We dived deep into the data using exploratory data analysis (EDA) to uncover hidden patterns and relationships between features and credit risk. Here's what we found:

Observations:

- Property Magnitude Impact: The chart suggests that the type of property significantly influences the proportion of bad and good loans.
- Real Estate Dominance: Among the property types, real estate exhibits the highest percentage of good loans, followed by life insurance and car ownership.
- No Known Property: This category shows the lowest percentage of good loans, indicating a potential risk factor.
- Consistent Bad Loan Percentage: Across all property types, the percentage of bad loans remains relatively consistent, ranging from approximately 20% to 40%.
- Data Imbalance: The chart might indicate a potential class imbalance issue, as the percentage of good loans consistently outnumbers bad loans.

Numerical Features: Kernel density estimation (KDE) plots revealed intriguing insights:
Debt-to-Income Ratio: Lower debt-to-income ratios were strongly linked to good creditworthiness. 📈📉


Credit Utilization: Similar to debt-to-income ratio, lower credit utilization indicated better credit standing. 💳
![image](https://github.com/user-attachments/assets/5ae9295a-6592-4adf-9135-2a277ef16e42)

Age: Age distribution hinted at potential differences between good and bad credit customers.

![image](https://github.com/user-attachments/assets/ab3ccc8d-c416-4013-9009-5e9005204177)

Categorical Features: We'll explore these further to uncover their impact on credit risk. 🕵️‍♀️
Data Preprocessing & Modeling 🤖
To prepare the data for our model, we transformed categorical features like 'checking_status', 'savings_status', and 'employment' into numerical values using OrdinalEncoder. 🔄

Then, we built a Decision Tree Classifier with a max depth of 5. It achieved an accuracy of 0.685 in predicting credit risk. 🌳

Key Findings & Next Steps 🚀
This dataset holds immense potential for credit risk assessment. Our analysis uncovered valuable patterns, but there's more to explore!

Deep dive into categorical features.
Uncover feature correlations.
Refine data preprocessing.
Experiment with different machine learning models.
Skills Utilized 🛠️
Exploratory Data Analysis (EDA) 📊
Data Visualization (KDE plots) 📈
Data Preprocessing (Ordinal Encoding) 🔄
Machine Learning (Decision Tree Classifier) 🌳
Model Evaluation (Accuracy) ✅
