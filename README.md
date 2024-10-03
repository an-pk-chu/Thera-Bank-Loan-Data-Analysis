# Thera-Bank-Loan-Data-Analysis

# Project Background
Thera Bank is focused on converting liability customers into personal loan clients while retaining their deposit relationships. Building on a successful campaign last year, which achieved a conversion rate of over 9%, the bank is seeking new, data-driven strategies to further improve these conversions. Our analysis reveals that targeting customers based on education level, income, and digital engagement can significantly enhance product adoption. By tailoring marketing campaigns to higher-educated and digitally active customers, and promoting personalized offers for young, high-income clients, the bank can improve conversion rates while effectively managing acquisition costs.
Insights and recommendations are provided on the following key areas:

- **Customer Demographic Analysis:**
- **Key Drivers of Loan and Spending Behaviors:** 
- **Online Banking Effectiveness:** 

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targed SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

The companies main database structure as seen below consists of four tables: table1, table2, table3, table4, with a total row count of X records. A description of each table is as follows:
- **Table 2:**
- **Table 3:**
- **Table 4:**
- **Table 5:**

[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

The visualizations highlight key trends across customer demographics and their financial behaviors. First, higher education levels are associated with greater adoption of personal loans and investment products like securities and CD accounts. Second, younger, higher-income customers show a higher likelihood of taking loans and exhibit greater credit card spending, while digital engagement is a significant driver—customers using online banking are more likely to adopt multiple financial products. To maximize product adoption and mitigate financial risks, the bank should focus on targeted marketing for higher-educated customers, promote online banking to boost overall engagement, and carefully manage risk among lower-income, high-spending customers.

<img width="968" alt="Screenshot 2024-10-02 at 8 01 25 PM" src="https://github.com/user-attachments/assets/2aefe009-d1d1-407a-b6c4-a13af75e06a8">


# Insights Deep Dive
### Customer Demographic Analysis:

* **Main insight 1.** The analysis indicates that education level plays a significant role in the adoption of financial products. Customers with graduate (Education level 2) and advanced (Education level 3) degrees have notably higher adoption rates for personal loans, securities accounts, and CD accounts compared to customers with undergraduate degrees.
  
* **Main insight 2.** Specifically, more than 60% of customers who hold securities and CD accounts are in the higher education categories, indicating that these customers are more informed or financially confident to adopt investment products.
  
* **Main insight 3.** In terms of family size, data shows that customers with smaller families (1-2 members) are more inclined to take personal loans compared to those with larger families (3-4 members). The stacked bar chart reveals a clear trend of higher personal loan acceptance among customers with fewer dependents, likely because of reduced financial burdens.
  

<img width="1077" alt="Screenshot 2024-10-02 at 8 09 42 PM" src="https://github.com/user-attachments/assets/88130376-09be-42fd-b03e-adebc6931c0f">


<img width="309" alt="Screenshot 2024-10-02 at 7 59 39 PM" src="https://github.com/user-attachments/assets/bac02919-a501-421b-91b0-8e176e347b18">



### Category 2:

* **Main insight 1.** The heatmap analysis reveals that younger customers (under 40) with higher incomes show a much higher probability of accepting personal loans. This demographic presents a promising target for personal loan products, as they are more willing and financially capable of handling credit.
  
* **Main insight 2.** The scatterplot of income vs. average credit card spending (CCAvg) demonstrates a positive correlation between income and credit card spending, indicating that higher-income customers tend to spend more on credit cards.
* 
* **Main insight 3.** Interestingly, the data also reveals that some lower-income customers still exhibit high credit card spending (more than $1,000 monthly). This pattern suggests financial stress or dependency on credit cards, which may increase the risk of delinquency.
  
* **Main insight 4.** Higher-income, younger customers are more inclined to take loans and spend more using credit cards. However, lower-income customers who spend significantly on credit cards pose a potential risk, requiring proactive measures to manage their financial health.

<img width="1094" alt="Screenshot 2024-10-02 at 8 05 28 PM" src="https://github.com/user-attachments/assets/0745c7b4-462e-45c5-ba90-de7b141fe255">

<img width="1093" alt="Screenshot 2024-10-02 at 8 05 50 PM" src="https://github.com/user-attachments/assets/d2fbd706-c101-47ef-a2a2-f13dd1154be7">

### Category 3:

* **Main insight 1.** Customers using online banking show significantly higher adoption rates for both personal loans and credit cards. Specifically, the clustered bar chart analysis shows that the percentage of customers with personal loans and credit cards is consistently higher among online banking users.
  
* **Main insight 2.** Over 70% of personal loan customers use online banking, suggesting that these individuals prefer digital interactions and are more open to adopting other bank products.
  
* **Main insight 3.** Trend Observation: There is a clear trend where digitally engaged customers are more likely to adopt additional financial products, indicating the effectiveness of online banking in facilitating cross-product engagement.

<img width="1071" alt="Screenshot 2024-10-02 at 8 08 48 PM" src="https://github.com/user-attachments/assets/36cc54c4-9d3f-4211-89cd-e324d1706053">


# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
