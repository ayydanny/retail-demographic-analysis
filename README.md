# Background and Overview
**This project explores retail spending behavior in 2023 across age and gender, using SQL for aggregation and Tableau for visualization.**  

The retail sales dataset simulates a dynamic retail environment in 2023, including customer demographics and sales information. This project evaluates how customer age and gender influence purchasing behavior and revenue. The goal is to identify demographic-driven patterns that can inform targeted marketing, product promotion, and strategic decision-making.

[retail_sales_dataset.csv](https://github.com/ayydanny/retail-demographic-analysis/blob/main/retail_sales_dataset.csv)  
[Final dataset](https://github.com/ayydanny/retail-demographic-analysis/blob/main/demographic_revenue.csv)  
[SQL queries + data inspection (pandas)](https://github.com/ayydanny/retail-demographic-analysis/blob/main/Retail%20Sales.ipynb)  
[Tableau dashboard](https://public.tableau.com/app/profile/daniel.lynn/viz/RetailDemographicAnalysis/Dashboard1)

The dataset consists of 9 columns for 1,000 transactions.  
<img width="407" height="198" alt="image" src="https://github.com/user-attachments/assets/47aad2cd-5c6f-4d5d-ad25-6b6d6587efa9" />

**Key Questions**
- Which age and gender groups contribute the most revenue?
- How do product preferences vary by demographic?
- What are actionable opportunities based on spending patterns?

## Executive Summary

**Gender** 
* Females' purchasing behavior is evenly distributed  
* Men's purchasing behavior leans much more towards electronics and less towards beauty

**Age**
* 18-24 and 45-54 spend the most on beauty
* 25-34 spends the most on clothing
* 55-64 spends the most on electronics

**Key insights**
* Clothing is overwhelmingly popular for 25-34
* Beauty takes a massive drop-off after 45-54
* Electronics tend to be more popular as age increases
* Despite the least total amount from 18-24, they spend the most per unit

<img width="1622" height="745" alt="image" src="https://github.com/user-attachments/assets/0943d7c2-9f9c-482f-bc85-c16d8588ba7e" />  

**Recommendations**  
Based on the demographic-driven insights from this analysis, the following recommendations are proposed:

- **Target product marketing by age group**  
  Clothing promotions could be prioritized toward customers aged 25–34, while electronics-focused campaigns may be more effective for customers aged 55–64, who show higher spending in this category.

- **Adjust gender-based product messaging**  
  Since male customers demonstrate a stronger preference for electronics and female purchasing is more evenly distributed, tailored messaging and product placement could improve engagement across genders.

- **Leverage high-value younger customers**  
  Although the 18–24 age group contributes lower total revenue, their higher spending per unit suggests an opportunity for premium or limited-product offerings aimed at younger consumers.

- **Use demographic insights to inform inventory and promotions**  
  Understanding how purchasing behavior shifts by age can help retailers better align inventory levels and promotional timing with demographic demand.

