# Bank Customer Churn Analysis

Exploratory analysis of 10,000 retail banking customers to
identify which segments are leaving and what the bank can do.

## Key findings
- 20.4% overall churn
- Customers aged 41-60 are 31% of the book but 61% of all churn
- Inactive members churn at 26.9% vs 14.3% for active members
- Germany churns at 32.4%, roughly double France and Spain
- Credit score, salary, tenure, and card ownership show no effect

## Data quality note
Zero-balance records are absent from the German data entirely
(0% vs ~48% in France and Spain). This made account balance look
predictive when it was really geography. Corrected in the analysis.

## Recommendations
1. Target retention at ages 41-60, where the volume is
2. Use inactivity as an early warning flag
3. Investigate the German market specifically

## Tools
Python, pandas, matplotlib, seaborn

## Running it
pip install pandas matplotlib seaborn jupyter
jupyter notebook Bank_Churn_EDA.ipynb
