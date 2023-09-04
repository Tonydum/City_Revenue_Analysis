# Comprehensive Analysis Report on New York City Budget And Financial Plan

## Table of Contents

- [Introduction](#introduction)
- [Data Dictionary](#data-dictionary)
- [Tools Used](#tools-used)
- [Data Cleaning Steps](#data-cleaning-steps)
- [Questions Answered](#questions-answered)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)


### Introduction:
The dataset under consideration was sourced from Kaggle and provides detailed financial information about a city's revenues over several years. This data, collected from different funding channels, offers invaluable insights into the city's financial trajectory and health. A thorough understanding of this data is essential for planning, budgeting, and making informed decisions about the city's financial health and priorities.

### Data Dictionary:
Fiscal Year: The financial year for which the data is reported.
Agency Name: The specific city agency responsible for the revenue.
Revenue Code Name: The type or category of the revenue.
Adopted Budget Amount: The initially planned or budgeted revenue amount.
Current Modified Budget Amount: The revised or updated budgeted revenue amount, reflecting any modifications made during the fiscal year.
Revenue Amount: The actual revenue collected or received by the city.

### Tools Used:
Python: The primary programming language for data manipulation and analysis.
pandas: A Python library for data analysis and manipulation.
matplotlib & seaborn: Python libraries for data visualization.
scikit-learn: A Python library for machine learning and predictive modeling.
statsmodels: A Python library for statistical models, hypothesis tests, and data exploration.

### Data Cleaning Steps:
Loaded the dataset and performed an initial examination.
Identified and handled missing values.
Removed rows where all revenue-related columns had zero values, considering them as non-contributory.
Standardized the capitalization in the 'Agency Name' column to ensure consistency.
Checked for any potential outliers in the revenue columns.

### Questions Answered:
1. How has the total revenue changed over the years?
Analyzed the yearly revenue trend.
Identified significant revenue sources and their trends over the years.
2. Which agencies consistently meet, exceed, or fall short of their adopted budget amounts?
Determined agencies with the highest discrepancies between adopted and actual revenues.
3. How often is the budget modified?
Assessed the frequency of budget modifications and identified the agencies and revenue sources with the most modifications.
4. Which revenue sources contribute the most to the city's finances?
Evaluated and visualized the contribution of each revenue source to the city's total revenue.
5. Predictive Analysis:
Built a model using linear regression to forecast revenues for the fiscal year 2023 based on historical data.

### Recommendations:
Monitoring Key Revenue Sources: Given that certain revenue sources, like "City Funds", contribute significantly to the city's finances, it's crucial to monitor and ensure the stability of these sources.

Budget Adherence: Some agencies consistently deviate from their adopted budgets. It's recommended to scrutinize the budgeting process of these agencies and provide necessary training or resources to enhance accuracy.

Regular Review: The budget is often modified. A regular review mechanism should be in place to understand the reasons behind frequent modifications and ensure they are justified.

Predictive Analysis: The linear regression model provides a basic forecasting capability. However, for more accurate predictions, especially over longer horizons, investing in more sophisticated models and gathering additional data might be beneficial.

### Conclusion
After an in-depth exploration of the city's revenue dataset, several key insights have emerged:

Trends Over Time: The city's revenue has generally shown a positive trend over the years, indicating economic growth and stability. However, like any financial trajectory, there are fluctuations which need close monitoring
Significant Revenue Sources: Certain revenue sources, particularly "City Funds," play a pivotal role in the city's finances. Ensuring the reliability and growth of these sources is vital for the city's economic health.
Budget Adherence: While many agencies adhere to their adopted budgets, some exhibit discrepancies. This divergence underscores the importance of accurate budget forecasting and, where discrepancies arise, understanding their root causes.
Budget Modifications: The frequent modifications to the budget highlight a dynamic financial landscape. While adjustments are sometimes necessary due to unforeseen circumstances, it's essential to ensure that such changes are well-justified and transparent.
Predictive Analysis: The linear regression model provided a basic forecasting capability, and while it offered a reasonable approximation, there's room for improving accuracy. Leveraging more sophisticated models and techniques could refine these predictions further.
