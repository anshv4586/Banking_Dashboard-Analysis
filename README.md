# 🏦 Banking Data - Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a banking dataset to understand customer financial behavior, relationships between variables, and key insights useful for business decision-making.

The analysis includes data cleaning, feature engineering, statistical summaries, and visualization of trends.

📂 Dataset
File used: Banking.csv
Contains customer-level banking data such as:
Age
Estimated Income
Bank Deposits
Loans
Credit Card Balance
Savings & Checking Accounts
Risk Weighting
Occupation, Nationality, etc.
⚙️ Tools & Libraries Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
🔍 EDA Process
1. Data Loading
Loaded dataset using Pandas
Previewed initial rows
2. Data Understanding
Checked dataset shape
Used .info() to understand data types
Identified numerical & categorical columns
3. Feature Engineering
Created Income Band:
Low (0 – 100K)
Mid (100K – 300K)
High (>300K)
4. Data Cleaning
Checked missing values
Converted Joined Bank to datetime format
5. Statistical Analysis
Generated descriptive statistics using .describe()
6. Categorical Analysis
Analyzed distributions of:
Risk Weighting
Occupation
Nationality
Income Band
Loyalty Classification
7. Correlation Analysis
Explored relationships between numerical variables
Identified strong and weak correlations
8. Data Visualization
Used Matplotlib & Seaborn for:
Pair plots
Correlation analysis
Relationship visualization
📊 Key Insights
💰 Deposits & Savings Behavior
Strong correlation between Bank Deposits and Saving Accounts
Indicates similar financial behavior patterns
📈 Income & Age Trends
Higher income and age → higher:
Savings
Superannuation
Deposits
🏠 Property Ownership
Weak correlation with banking features
Suggests influence of external factors (market, inheritance)
🏢 Business vs Personal Banking
Business lending behaves differently from personal finances
Moderate link between business loans and general bank loans
📁 Project Structure
📦 Banking-EDA
 ┣ 📜 BankingEDA.ipynb
 ┣ 📜 Banking.csv
 ┗ 📜 README.md
🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/Banking-EDA.git
Install dependencies:
pip install pandas numpy matplotlib seaborn
Run the notebook:
jupyter notebook BankingEDA.ipynb
🎯 Future Improvements
Apply Machine Learning models
Customer segmentation (Clustering)
Predict loan default risk
Build dashboard (Power BI / Streamlit)
🤝 Contributing

Feel free to fork this repo and improve the analysis.

📬 Contact

For queries or collaboration:

GitHub: anshv4586
