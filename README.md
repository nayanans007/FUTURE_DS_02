CUSTOMER RETENTION & CHURN ANALYSIS

CONTEXT

Subscription-based businesses and telecom companies rely heavily on customer retention for stable revenue and long-term growth. Even a small increase in customer churn can significantly impact profitability and customer acquisition costs. This project focuses on analyzing customer churn data to identify why customers leave the platform, which customer groups are most at risk, and what business strategies can improve customer retention.

Using Excel and Python libraries such as Pandas, Matplotlib, and Seaborn, the dataset was cleaned, analyzed, and visualized to uncover meaningful customer behavior patterns and actionable business insights.

DATASET INFORMATION

| Field | Details |
|---|---|
| Dataset | Telco Customer Churn Dataset |
| Source | Kaggle |
| Records Analyzed | 7,043 customers |
| Total Columns | 21 customer-related variables |
| Dataset Type | Customer retention and subscription behavior dataset |

OBJECTIVE

The objective of this project was to analyze customer churn behavior and identify key retention drivers that influence whether customers stay or leave the company. The analysis was designed to help answer important business questions such as:

- Why are customers leaving the platform?
- Which customer segments are most likely to churn?
- How long do customers typically remain active?
- Which services improve customer retention?
- What actions can help reduce churn and improve long-term customer loyalty?

The project aimed to provide business-focused insights and practical recommendations that could help a subscription-based company improve customer satisfaction and retention performance.

TOOLS USED

- Microsoft Excel
- Python
- Pandas
- Matplotlib
- Seaborn
- VS Code
- Jupyter Notebook

PROJECT WORKFLOW

- Imported the raw churn dataset into Microsoft Excel and created a separate cleaned dataset for analysis
- Cleaned and organized the dataset by checking missing values, formatting numerical columns, and verifying customer-related fields
- Created customer tenure groups to segment users into New, Mid-Term, and Long-Term customers
- Loaded the cleaned dataset into Python using Pandas for analysis
- Performed exploratory data analysis (EDA) to analyze churn trends, customer lifetime patterns, contract behavior, pricing trends, and retention drivers
- Created visualizations using Matplotlib and Seaborn to identify churn patterns and customer behavior trends
- Generated business insights and practical recommendations based on customer retention analysis

KEY PERFORMANCE INDICATORS (KPIs)

| KPI | Value |
|---|---|
| Total Customers | 7,043 |
| Customers Churned | 1,869 |
| Customers Retained | 5,174 |
| Overall Churn Rate | 26.5% |
| Average Tenure of Retained Customers | ~37.6 months |
| Average Tenure of Churned Customers | ~18 months |

KEY INSIGHTS

- The company has an overall churn rate of approximately 26.5%, meaning nearly one out of every four customers discontinued the service. Although most customers remained with the company, the churn volume is still significantly high and represents a major retention challenge for the business.

- Customers with month-to-month contracts showed the highest churn risk. Approximately 42.7% of month-to-month customers churned, compared to only 11.3% for one-year contracts and 2.8% for two-year contracts. This clearly shows that long-term contracts strongly improve customer retention and customer loyalty.

- Customer tenure analysis revealed that churn happens much earlier in the customer lifecycle. Customers who churned stayed for only around 18 months on average, while retained customers stayed for approximately 38 months. This suggests that new customers are at the highest risk of leaving the platform.

- Customers who churned paid significantly higher monthly charges compared to retained customers. Churned customers paid approximately $74 per month on average, while retained customers paid around $61. This indicates that higher pricing and customer value perception may influence churn behavior.

- Tech support emerged as one of the strongest customer retention drivers. Customers without tech support showed approximately 41.6% churn, while customers with tech support had only around 15.2% churn. This suggests that customer support quality plays a major role in improving customer satisfaction and retention.

- Fiber optic internet customers showed extremely high churn rates of approximately 41.9%, compared to only 19% for DSL customers. This suggests that premium internet users may have higher expectations regarding pricing, service quality, or customer experience.

- Visual analysis of tenure distribution showed that churn is heavily concentrated during the early months of the customer journey. Customers who remain with the company for longer periods become significantly more loyal over time.

VISUAL ANALYSIS

1. CUSTOMER CHURN DISTRIBUTION

This graph shows the overall number of retained and churned customers. Although most customers stayed, the churn count remains significantly high.

Approximately 26.5% of customers churned, meaning nearly one out of every four customers left the company. This highlights a major customer retention challenge.

2. CHURN BY CONTRACT TYPE

This graph compares churn across different contract types. Month-to-month customers showed the highest churn, while long-term contract customers showed very low churn.

Long-term contracts strongly improve customer retention. Customers with month-to-month plans are far more likely to leave the company.

3. CUSTOMER TENURE DISTRIBUTION BY CHURN

This graph shows customer churn based on tenure. Most churn occurs during the early months of the customer lifecycle.

New customers are at the highest risk of churn, while long-term customers tend to remain loyal. Improving early customer experience can help increase retention.

4. MONTHLY CHARGES DISTRIBUTION BY CHURN

This graph compares churn patterns across different monthly charge ranges. Higher-paying customers showed higher churn levels.

Customers with expensive plans are more likely to churn, possibly due to pricing concerns or higher service expectations.

INTERPRETATION

The churn analysis clearly shows that customer retention is strongly influenced by contract commitment, pricing, customer support, and customer lifecycle stage. The analysis reveals that customers with shorter commitments and higher monthly charges are significantly more likely to leave the platform. This indicates that customer loyalty and retention improve when customers remain engaged with the company for longer periods.

The findings also highlight the importance of customer support and service experience in retention management. Customers who lacked technical support were far more likely to churn, suggesting that support quality and customer assistance play a major role in customer satisfaction. Similarly, fiber optic users demonstrated very high churn rates despite paying premium prices, indicating that higher-paying customers may have stronger expectations regarding service quality and value.

The project also demonstrates that churn is not random. Clear customer behavior patterns exist across contract type, tenure, pricing, and service usage. These insights can help businesses proactively identify high-risk customers and implement targeted retention strategies before customers decide to leave the platform.

Overall, the analysis shows how customer retention analytics can help businesses reduce churn, improve customer loyalty, and make better data-driven business decisions using Python-based analytics tools.

RECOMMENDATIONS

1. Encourage Long-Term Contracts

Since month-to-month customers showed the highest churn risk, the company should encourage customers to shift toward one-year and two-year plans through:

- discounted annual plans
- loyalty rewards
- bundled subscription benefits

2. Improve Early Customer Experience

New customers are the most likely to churn during the initial months. The company should strengthen:

- onboarding experience
- customer engagement
- first-year customer support
- personalized retention campaigns

3. Improve Value for Premium Customers

Customers paying higher monthly charges churned more frequently. The business should:

- improve premium service quality
- provide additional value-added features
- strengthen customer satisfaction for higher-paying users

4. Strengthen Technical Support Services

Since customers without tech support showed very high churn rates, the company should:

- improve accessibility to tech support
- offer faster issue resolution
- encourage support plan adoption
- improve customer service quality

5. Investigate Fiber Optic Customer Experience

Fiber optic users showed extremely high churn rates despite being premium customers. The company should investigate:

- pricing concerns
- service quality issues
- network performance
- customer satisfaction among fiber users

CONCLUSION

This project successfully transformed raw customer churn data into meaningful business insights using Excel, Python, Pandas, Matplotlib, and Seaborn. The analysis identified major churn patterns, high-risk customer segments, retention drivers, and customer lifetime behaviors that directly impact business growth and customer retention.

The project demonstrated how data analytics can help businesses understand customer behavior more effectively and create actionable strategies to improve retention and reduce churn. Overall, this analysis highlights the importance of customer-focused decision-making and the role of analytics in improving long-term business performance.
