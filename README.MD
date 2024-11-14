# HYBRID BANK CHURN PROJECT




## OVERVIEW


`PROBLEM STATEMENT`

Hybrid Bank seeks to enhance its decision-making processes by analyzing customer data to gain deeper insights into demographics, financial characteristics, and engagement patterns. The objective is to identify trends in service usage, account activity, and customer satisfaction. The findings will highlight key areas for business improvement, including opportunities to optimize services and develop strategies to improve customer retention, ultimately enabling the bank to refine its offerings and better align with customer needs.



`Objective`

Using the Dataset, we would try to answer Questions that will focus on idetifying trends and patterns in Customer Engagement, such as service usage, account activity, and Customer Satisfaction. Answering Questions like:

- `Demographic Analysis`: Analyze the distribution of customers based on geography, gender, and age. Identify any demographic segments (e.g., by geography or gender) that have a significantly different credit score, balance, or other financial metrics.

 
- `Customer Engagement Patterns`: Investigate the relationship between customer tenure and engagement (such as the number of products owned, HasCrCard, and IsActiveMember). Analyze the impact of tenure on customer behavior, especially focusing on long-term customer patterns (e.g., do longer-tenured customers tend to hold more products or have higher balances?).

- `Financial Performance`: Explore credit score distribution and identify which customer segments (e.g., age, gender, geography) tend to have higher or lower credit scores. Analyze customer balance and estimated salary patterns and compare them across different demographic groups.
  
- `Exited Customer Analysis`: Compare the financial and demographic characteristics of customers who exited the bank versus those who remain active. Identify possible factors (e.g., age, credit score, balance) associated with customers exiting the bank.
  
- `Customer Segmentation`: Based on the available data, identify distinct customer segments (e.g., high-balance vs. low-balance customers) and analyze their unique characteristics. Provide insights into how the bank could optimize its services for each segment, such as offering tailored products to certain demographics or improving engagement with less active members.



`Approach`

To achieve this, we are going to approach the analysis using the CRISP-DM (Cross-Industry Standard Process for Data Mining) Framework.

- Properly understand and explore the data
- Prepare the data for analysis
- Answer questions to help us achhieve our objectives
- Draw conclusions
- Prepare summaries



#DATA

`Field`:  Description	

`CustomerId`:  A unique identifier for each customer

`Surname`:  The customer's last name	

`CreditScore`:  A numerical value representing the customer's credit score

`Geography`:  The country where the customer resides (France, Spain or Germany)

`Gender`:  The customer's gender (Male or Female)


`Age`:	The customer's age		

`Tenure`:  The number of years the customer has been with the bank

`Balance`:	The customer's account balance

`NumOfProducts`:  The number of bank products the customer uses (e.g., savings account, credit card)

`HasCrCard`:  Whether the customer has a credit card (1 = yes, 0 = no)


`IsActiveMember`:  Whether the customer is an active member (1 = yes, 0 = no)
`EstimatedSalary`:  The estimated salary of the customer

`Exited`:  Whether the customer has churned (1 = yes, 0 = no)
				
				
# Insights

The following insights were drawn from analyzing the data:

This analysis of Hybrid Bank's customer data, segmented by geography and various customer attributes, provides valuable insights into customer demographics, engagement patterns, financial performance, and retention trends across three key markets: **France, Spain, and Germany**.


`DEMOGRAPHIC ANALYSIS`

Hybrid Bank's customer base has a **55% male and 45% female distribution** across all three countries, with **France** having the largest number of customers, followed by **Spain and Germany** reflecting the bank's strong market presence in France. This suggests that efforts in France should focus on increasing value from this substantial customer base, while Spain and Germany present opportunities for growth and retention.

![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Customers by Geography.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Customers by Gender.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Customers by Geography and Gender.png)


`Customer Engagement Patterns`

In terms of customer engagement, those with **5+ years of tenure** at Hybrid Bank exhibit the highest levels of product ownership, suggesting that long-term customers are more likely to hold multiple products. While customers with shorter tenures (1–5 years) also have multiple products, the total number of products held decreases slightly over time. However, there is a slight increase in product engagement among customers with 5+ years of tenure, suggesting strong customer retention and possible renewed loyalty among long-term customers. Active membership is also highest among long-tenure customers, while newer customers (0–1 years) show lower engagement. Therefore, Hybrid Bank can benefit from introducing retention programs or incentives aimed at retaining customers in their early years while continuing to foster loyalty among its long-tenured clients.

![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Number of Products Owned Across Tenure.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Number of Customers with and without Credit Cards.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Active Membership Across Tenure.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Comparison of Products Owned and Balance by Tenure.png)


`Financial Performance`

In terms of financial performance, customers aged **65 and above** have slightly higher credit scores compared to those aged 18–64. This could be attributed to older customers having more experience managing credit and a longer credit history. While the difference in credit scores is not substantial, it highlights the creditworthiness of the older customer segment, which could be linked to their financial stability. While the differences in credit scores across age groups are not large, Hybrid Bank should leverage this insight to offer personalized products that suit the financial behaviors and needs of all age groups.

![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Average Credit Score by Age Group.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Credit Score by Gender.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Credit Score Distribution by Geography.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Average Customer Balance by Geography.png)


`Exited Customers Analysis`

The retention rate at Hybrid Bank is generally strong, with the majority of customers remaining with the bank. However, a significant number—around **2,037 customers**—have exited, representing a notable, though relatively small, proportion of the customer base. **Germany** has the highest exit rate at **32.5%**, indicating potential retention challenges in this market. In contrast, **France and Spain** exhibit lower exit rates, around **16%**, demonstrating relatively better customer loyalty in these countries. The data also suggests that **inactive customers** are more likely to leave, pointing to a need for stronger **re-engagement strategies** to retain these customers and reduce the exit rate further. Special attention should be given to Germany, where the bank could introduce personalized services, loyalty programs, or customer feedback initiatives to better understand and address the reasons for customer exits.

![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Customer Exit Distribution.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Active Members vs Exited Customers.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Geography vs Exited Customers.png)


`Customer Segmentation`

Customer segmentation by balance highlights significant geographical differences. **Germany** stands out with a much larger proportion of **high balance customers**, suggesting that this market consists of a wealthier demographic or more valuable customers.This suggests that Hybrid Bank's efforts in Germany should focus on **high-value retention strategies** that cater to wealthier clients, such as premium banking services, personalized financial advice, or exclusive product offerings. This, however, contrasts with **France**, where **low balance customers** outnumber high balance ones, suggesting a broader customer base with varying financial profiles. The bank could explore offering financial products designed to help these customers grow their wealth, such as savings incentives, investment opportunities, or tailored credit products. **Spain** displays a more balanced distribution between high and low balance customers, though low balance accounts still outnumber high balance ones.

![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\High vs Low Balance Customers by Geography.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Distribution of Customer Account Balances.png)
![Visualization](C:\Users\DEBBY\Downloads\Bank Churn Project\Images\Average Balance by Gender.png)


Overall, the demographic, financial, and engagement data offer key insights into **Hybrid Bank's customer base**. Germany presents a wealthier, high-value segment with a retention challenge, while France and Spain have more diverse customer bases but relatively lower balances. The retention strategies should focus on engaging both new and inactive customers, especially in Germany, to reduce the exit rate and build long-term loyalty. Additionally, understanding the financial behaviors of older customers and those with longer tenure can help shape more targeted product offerings and engagement strategies.



# Conclusion, Recommendation and Future Work

To maximize growth and retention, Hybrid Bank should focus on the following strategies:

- Introduce targeted retention efforts in Germany, focusing on high-balance customers and addressing reasons for high exit rates through personalized communication and loyalty initiatives.

- Reactivate dormant or zero-balance accounts by offering incentives such as fee waivers or product bundles to encourage more financial activity.

- Strengthen early-stage customer engagement with welcome offers, product education, and financial tools to enhance loyalty and product adoption in the early years

- Offer personalized products for older, creditworthy customers, such as investment services or tailored loans, and design strategies that cater to the wealthier segments in Germany and the lower-balance segments in France.

**By implementing these strategies, Hybrid Bank can enhance customer loyalty, increase product engagement, and capture more value across its diverse geographical markets.**

# Executive Summary

Link to executive summary : [See Executive Summary](https://docs.google.com/document/d/18HaMpsLZwTkRcfILPnA0YX6QnIVF9QNEalr9_0Dic_4/edit?usp=drive_link)
