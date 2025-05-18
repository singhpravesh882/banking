# banking
## End-to-End Project Overview  

An end-to-end banking EDA project utilized Python for data cleaning and analysis, MySQL for data storage and queries, and Power BI for creating the final dashboard to showcase insights and KPIs to stakeholders.


### Files overview

1. Banking.xlsx - Dataset
2. Banking_EDA - Code snippets including import queries from sql, and exploratory analysis using univariate and bivariate techniques
3. Banking_dashboard - A Power BI dashboard including visualizations


### Data Analysis Techniques  

Descriptive statistics in EDA provide insights into distribution and summary of numerical columns, such as age ranging from 17 to 85 with 75% of people above 69 years old.

Univariate analysis of categorical columns like BR ID, gender ID, and credit cards reveals distribution patterns, such as equal gender distribution and 66% of customers having one credit card.

Bivariate analysis with hue on categorical columns uncovers insights, e.g., 95% of three credit card holders are male, suggesting gender differences in credit card usage.

Heatmap correlation analysis reveals strong positive correlations: bank deposits with checking accounts (0.9), savings accounts (0.9), and foreign currency accounts (0.41).  


### Dashboard Design and Visualization  

Banking dashboard design includes key metrics like total clients, loans, deposits, fees, credit card balance, and gender slicer, with additional date slicer for year/month based on requirements.  

Used conditional columns in Power BI to categorize estimated income into high, medium, and low income bands based on defined thresholds (e.g., >=300k for high, >=100k for medium).

Replaced numeric values in Power BI slicers with descriptive labels (e.g., 1 to Retail, 2 to Institutional) for better understanding.

Created buttons in Power BI for page navigation between different analysis sections (e.g., Loan Analysis, Deposit Analysis, Summary) to improve user experience and dashboard interactivity.
