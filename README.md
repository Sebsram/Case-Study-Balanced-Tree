# Case Study: Balanced Tree

![icon](https://user-images.githubusercontent.com/130475600/235360248-1bb6d8f1-2e85-45d5-8af6-86c0986ff37a.PNG)

# Problem Statement:
Balanced Tree Clothing Company prides themselves on providing an optimised range of clothing and lifestyle wear for the modern adventurer!

Danny, the CEO of this trendy fashion company has asked you to assist the team’s merchandising teams analyse their sales performance and generate a basic financial report to share with the wider business.

# Available Data:
For this case study there is a total of 4 datasets for this case study - however you will only need to utilise 2 main tables to solve all of the regular questions, and the additional 2 tables are used only for the bonus challenge question!

**Product Details**

balanced_tree.product_details includes all information about the entire range that Balanced Clothing sells in their store.

![product_details](https://user-images.githubusercontent.com/130475600/235360284-5b2b791e-18a6-4a5f-8d3f-fdcec4b85bb1.PNG)

**Product Sales**

balanced_tree.sales contains product level information for all the transactions made for Balanced Tree including quantity, price, percentage discount, member status, a transaction ID and also the transaction timestamp.

![product_sales](https://user-images.githubusercontent.com/130475600/235360333-f9a23c9d-a690-4f9a-8171-7ccfcc885c1a.PNG)

**Product Hierarchy**

Thes tables are used only for the bonus question where we will use them to recreate the balanced_tree.product_details table.

balanced_tree.product_hierarchy

![product_hier](https://user-images.githubusercontent.com/130475600/235360357-276e2c0f-dbba-4b11-a5b5-182b9be6e47d.PNG)

**Product Prices**

![prices](https://user-images.githubusercontent.com/130475600/235360374-81dfe9ac-d22d-4fbb-ab1d-43eea45ef7cb.PNG)

# Case Study Questions

**High Level Sales Analysis**

1. What was the total quantity sold for all products?
2. What is the total generated revenue for all products before discounts?
3. What was the total discount amount for all products?

**Transaction Analysis**

1. How many unique transactions were there?
2. What is the average unique products purchased in each transaction?
3. What are the 25th, 50th and 75th percentile values for the revenue per transaction?
4. What is the average discount value per transaction?
5. What is the percentage split of all transactions for members vs non-members?
6. What is the average revenue for member transactions and non-member transactions?

**Product Analysis**

1. What are the top 3 products by total revenue before discount?
2. What is the total quantity, revenue and discount for each segment?
3. What is the top selling product for each segment?
4. What is the total quantity, revenue and discount for each category?
5. What is the top selling product for each category?
6. What is the percentage split of revenue by product for each segment?
7. What is the percentage split of revenue by segment for each category?
8. What is the percentage split of total revenue by category?
9. What is the total transaction “penetration” for each product? (hint: penetration = number of transactions where at least 1 quantity of a product was purchased divided by total number of transactions)
