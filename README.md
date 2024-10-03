# Thera-Bank-Loan-Data-Analysis

# Project Background
Thera Bank is focused on converting liability customers into personal loan clients while retaining their deposit relationships. Building on a successful campaign last year, which achieved a conversion rate of over 9%, the bank is seeking new, data-driven strategies to further improve these conversions. Our analysis reveals that targeting customers based on education level, income, and digital engagement can significantly enhance product adoption. By tailoring marketing campaigns to higher-educated and digitally active customers, and promoting personalized offers for young, high-income clients, the bank can improve conversion rates while effectively managing acquisition costs.
Insights and recommendations are provided on the following key areas:

- **Customer Demographic Analysis:**
- **Key Drivers of Loan and Spending Behaviors:** 
- **Online Banking Effectiveness:** 


# Data Structure & Initial Checks

The file "bank_loan.csv" contains data on 5,000 customers, including demographic information (such as age and income), details about the customer's relationship with the bank (e.g., mortgage, securities account), and their response to a previous personal loan campaign (indicated by "Personal Loan"). Out of these 5,000 customers, only 480 (or 9.6%) accepted the personal loan offered in the earlier campaign.

The dataset has no missing (NaN) values. It includes a combination of numerical and categorical attributes, with all categorical data represented numerically.

<img width="429" alt="Screenshot 2024-10-02 at 8 21 23 PM" src="https://github.com/user-attachments/assets/bd96dd34-4c9c-440e-9971-430598bda26e">

**The Python codes to clean the data for this analysis can be found here [Google Colab](https://colab.research.google.com/drive/1s_e7js7pBFI9qygYm1dyehvHNTLbJv6k?usp=sharing)**.

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

Based on the insights and findings above, we recommend that the Marketing and Customer Engagement Team consider the following:


**Focus on Smaller Families: Smaller families are more likely to adopt personal loans**. **Create tailored loan products with flexible terms to attract this segment**.

**Young, High-Income Customer Strategy**: Younger, high-income customers have a high probability of loan acceptance. **Offer personalized loan products targeted to this group to maximize engagement.**

**Promote Online Banking**: Online banking users adopt more products. Promote digital engagement by offering incentives for online banking to boost product adoption.

**Risk Management for Lower-Income Customers**: Lower-income customers with high credit card spending pose financial risks. Implement financial counseling to manage potential credit issues.


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

- Education Levels Grouping: Education levels 2 (graduate) and 3 (advanced) were combined for broader comparison.

- Handling Missing Data: Missing income and age values were imputed to ensure comprehensive analysis.

- Online Banking Accuracy: Assumed data on online banking usage was accurate for insights on digital engagement.





