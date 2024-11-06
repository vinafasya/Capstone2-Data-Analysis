# Capstone2-Data-Analysis
Tableau Story: https://public.tableau.com/views/CapstoneModule2_VinaF_/Story?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


Video: https://drive.google.com/file/d/1M4quyXqwSSSslu32qS7b4U990ysN0qnr/view?usp=drive_link

Background
The "Supermarket Customers.csv" dataset provides comprehensive information about supermarket customers. It includes demographic details such as age, education, marital status, income, and household composition (number of children/teens). Additionally, it captures shopping behavior, including spending on various product categories, preferred purchasing channels, and responses to marketing promotions. This dataset was gathered by the supermarket to gain a deeper understanding of customer preferences and behaviors.

Problem Statement
The goal of this analysis is to determine how customer demographic factors—such as age, education, marital status, income, and household composition (number of children/teens)—influence their shopping behavior at the supermarket. Specifically, we aim to understand how these characteristics affect spending across product categories like wine, fruits, meat, fish, sweets, and gold.

This analysis will be used to provide meaningful insights that can help in various aspects of supermarket operations, including:

* Customer Segmentation: Identifying distinct customer segments based on their demographic attributes and purchasing behavior.
* Focused Marketing Strategies: Developing tailored marketing campaigns to appeal to specific customer groups, enhancing the effectiveness of promotions.
* Product Development and Offerings: Recommending improvements or changes to product offerings that match customer preferences, driving increased satisfaction and sales.
* Actionable Stakeholder Recommendations: Delivering clear, data-driven recommendations for stakeholders to make informed decisions regarding marketing, inventory management, and customer engagement strategies.

Objectives
1. Understand how customer demographic characteristics (age, education, marital status, income, household composition) influence their shopping behavior, particularly in terms of spending across various product categories.
2. Identify the most profitable customer segments and determine effective marketing strategies for each segment.
3. Optimize inventory management and merchandising based on customer preferences and shopping behavior.


This dataset contains information related to customer demographics, products, promotions, and locations. The supermarket_customers dataset consists of 29 columns, which are: 
#People
* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if the customer complained in the last 2 years, 0 otherwise

#Products
* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years

#Promotion
* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise
* Z_CostContact: unknown, no information about this column on the guidance
* Z_Revenue: unknown, no information about this column on the guidance	

#Place
* NumWebPurchases: Number of purchases made through the company’s website
* NumCatalogPurchases: Number of purchases made using a catalog
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to the company’s website in the last month


