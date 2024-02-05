# Customer-Demographics
---


### **Problem Statement**:
---
In this project, I analyzed customer data using formulas, PivotTables, and PivotCharts in Excel. The dataset includes information such as customer demographics, banking details, and account activity. The goal is to segment customers and analyze their behavior to develop an effective marketing strategy.
### **Dataset**:
---
1. ID: This column represents the unique identifier for each customer in the dataset. It is used to differentiate and track individual customers.
2. Gender: This column indicates the gender of each customer, distinguishing between male and female customers. It helps analyze gender-based patterns and preferences.
3. Age: This column represents the age of each customer. It provides insights into the age distribution of the customer base and allows for age-based segmentation and analysis.
4. Region_Code: This column represents the region code or geographical location associated with each customer. It helps analyze customer distribution across different regions and identify regional patterns.
5. Occupation: This column specifies the occupation or job category of each customer. It allows for segmentation and analysis based on occupation-related factors.
6. Channel_Code: This column indicates the channel code through which customers interact with the company, such as online, offline, or through a specific channel. It helps analyze customer preferences and channel-specific behaviors.
7. Vintage: This column represents the vintage or the duration of the customer's relationship with the company. It provides insights into customer loyalty and engagement.
8. Credit_Product: This column indicates whether the customer has a credit product (such as a loan or credit card) with the company. It helps analyze the impact of credit products on customer behavior and engagement.
9. Avg_Account_Balance: This column represents the average account balance of each customer. It provides insights into customer financial status and potential purchasing power.
10. Is_Active: This column indicates whether the customer is active or inactive in terms of account usage or engagement. It helps analyze customer activity levels and their impact on business performance.


### **Tools**
---
Excel Workbook 

### Data Cleaning 
---

1. Remove Duplicates: *No*
     - *No* duplicates in the dataset
2. Null Values: *Yes*
   - Replace the null value in the Credit-Product Column with ***No***


## EDA 
---
Created a Conditional column to split the age column into different age group in other to understand customers account activities  by age 
``` excel
syntax
=IF(C2<40,"Youth",IF(C2<65,"Advance","Old"))
```
### KPI's
---
1. Total Average Vintage :
   - 47%
2. Total Customer Count :
 - 105,312
3. Total Avg Balance :
   - £119B
4. Total Regoin Count:
   - 35
5. Gender Distribution Of Customers
   - Male (57,705(55%))
   - Female (43,192(45%))


 ### Segmentation 
 ---
 In the dataset they are different segment like Occupation, Gender,Channel code And Credit product segmentation, each of this segment will be well analysed to understand customers behaviors for marketing decisions.   

 1. Occupation
    - Entreprenuer
       - Avr Vintage 71%
       - Total Customers (1076)
       - Total Average balance (1B)
     - Other
       - Avg Vintage 55%
       - Total Customers(30,131)
       - Total Average Balance (36B)
     - Salaried
       - Average vintage (26)
       - Total Customers(30913)
       - Total Average Balance (32B)
     - Self Employed
        - Average Vintage (56%)
        - Total Customers (43192)
        - Total Average Balance (£49B)
2. Age Bracket
   - Advance (Age 40-65)
      - Average Vintage (64%)
      - Total Customers(47,952)
      - Total Average Balance(£57B)
    - Old (Age 65 and Above )
       - Average Vintage (71%)
       - Total Customers (10,602)
       - Total Avialable Balance(£14B)
     - Youth (Age Below 40)
       -  Average Vintage (24%)
       -  Total Customers (46,758)
       -  Total Available Balance (£47B)
3. Channel Code
   - X1
      - Average Vintage (25%)
      - Total Customers (44,484)
      - Total Available Balance (£46B)
   - X2
      - Average Vintage (55%)
      - Total Customers (29,176)
      - Total Available Balance (£33B)
   - X3
      - Average Vintage (75%)
      - Total Customers (29,269)
      - Total Available Balance (£37B)
   - X4
      - Average Vintage (12%)
      - Total Customers (2,383)
      - Total Available Balance (£2B)
4. Credit Product Availability
   - No
      - Average Vintage(45%)
      - Total Customers(74,130)
      - Total Available Balance(£82B)
   - Yes
      - Average Vintage (52%)
      - Total Customers (31,182)
      - Total Available Balance (£36B)
5. Account Status
   - No
      - Average Vintage (41%)
      - Total Customers (63,797)
      - Total Available Balance (£69B)
    - Yes
      - Average Vintage (55%)
      - Total Customers (41,515)
      - Total Available Balance (£50B)
     
6. Gender
   - Male
      - Average Vintage (51%)
      - Total Customers (57,705)
      - Total Available Balance (£66B)
    - Female
      - Average Vintage (42%)
      - Total Customers (47,607)
      - Total Available Balance (£52B)





  






