# vanguard-ab-tes

Overview
This project focuses on performing A/B testing for Vanguard's user experience or product performance. The goal is to evaluate the effectiveness of two different variants (A and B) in driving user engagement and conversion rates.

🔍 Objective
To determine whether Variant B performs significantly better than Variant A in terms of a key metric (e.g., conversion rate, click-through rate, etc.) using statistical analysis techniques.

📁 Dataset
The dataset contains the following:

User ID

Group (A or B)

Converted (0 or 1)

Timestamp

Other user-level metadata (optional)

🛠️ Tools & Libraries
Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)

Jupyter Notebook

Statistical hypothesis testing (Z-test, Chi-square)

🧪 Methodology
Data Cleaning & Preprocessing

Handled missing values

Checked for duplicate entries

Balanced group distribution

Exploratory Data Analysis (EDA)

Visualized group-level conversion rates

Plotted distribution of users across segments

A/B Testing

Set up Null and Alternative Hypotheses

Conducted statistical significance testing (Z-test for proportions)

Calculated p-value and confidence intervals

Conclusion

Interpreted results to support or reject the null hypothesis

Offered data-driven recommendations

📈 Key Findings
Variant B showed a +X% increase in conversion rate compared to Variant A

P-value = 0.XXX → Statistically significant at 95% confidence level

Recommendation: Roll out Variant B across all users

📎 Files Included
vanguard_ab_test_analysis.ipynb – Main analysis notebook

data/ – Folder with cleaned datasets

charts/ – Visualizations from EDA and test results
