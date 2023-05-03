# High Level Sales Analysis

**1. What was the total quantity sold for all products?**

![a1](https://user-images.githubusercontent.com/130475600/235455360-14fd4be7-b829-4f1d-b007-e9ff28e9a356.PNG)

| t_quantity |
| ---------- |
| 45216      |

**2. What is the total generated revenue for all products before discounts?**

![image](https://user-images.githubusercontent.com/130475600/235456013-d5e7555a-eda6-4929-b012-b4d6fe75d0eb.png)

| product_name                     | total_rev |
| -------------------------------- | --------- |
| Blue Polo Shirt - Mens           | 217683    |
| Grey Fashion Jacket - Womens     | 209304    |
| White Tee Shirt - Mens           | 152000    |
| Navy Solid Socks - Mens          | 136512    |
| Black Straight Jeans - Womens    | 121152    |
| Pink Fluro Polkadot Socks - Mens | 109330    |
| Khaki Suit Jacket - Womens       | 86296     |
| Indigo Rain Jacket - Womens      | 71383     |
| White Striped Socks - Mens       | 62135     |
| Navy Oversized Jeans - Womens    | 50128     |
| Cream Relaxed Jeans - Womens     | 37070     |
| Teal Button Up Shirt - Mens      | 36460     |

**3. What was the total discount amount for all products?**

![a3](https://user-images.githubusercontent.com/130475600/235456383-4f9386d3-4a24-4dec-9773-89a76e785e48.PNG)

| total_discount |
| -------------- |
| 156229         |

# Transaction Analysis

**1. How many unique transactions were there?**

![a4](https://user-images.githubusercontent.com/130475600/235456942-d84fae2c-dc40-4dd7-9c28-0dc886411840.PNG)

| unique_transactions |
| ------------------- |
| 2500                |

**2. What is the average unique products purchased in each transaction?**

![a5](https://user-images.githubusercontent.com/130475600/235457372-c76b79fd-488c-493b-bada-e5ac06a5f3e0.PNG)

| unique_average |
| -------------- |
| 6              |

**3. What are the 25th, 50th and 75th percentile values for the revenue per transaction?** 

![a6](https://user-images.githubusercontent.com/130475600/235461570-8de88e86-7bad-4ebd-a11d-e954727b7466.PNG)

| Percentile_25 | Percentile_50 | Percentile_75 |
| -------------- | ------ | ------ |
| 375.75         | 509.5 | 647 |

**4. What is the average discount value per transaction?**

![a7](https://user-images.githubusercontent.com/130475600/235462829-c44ad839-8944-4783-98f6-f96df005c4f8.PNG)

| avg_discount_value |
| ------------------ |
| 62                 |

**5. What is the percentage split of all transactions for members vs non-members?** 

![a8](https://user-images.githubusercontent.com/130475600/235464313-663fa357-86ca-4a2e-95f6-583b3baca560.PNG)

| member_split | non_member_split |
| ------------ | ---------------- |
| 60.00        | 40.00            |

**6. What is the average revenue for member transactions and non-member transactions?**

![a9](https://user-images.githubusercontent.com/130475600/235465280-1866bc19-2b63-4902-89e1-76b9b52e3301.PNG)

| member | average |
| ------ | ------- |
| false  | 515     |
| true   | 516     |

# Product Analysis

**1.What are the top 3 products by total revenue before discount?**

![a10](https://user-images.githubusercontent.com/130475600/235466262-8497a86b-fda8-4dc5-975c-51f33b69d255.PNG)

| product_name                 | revenue |
| ---------------------------- | ------- |
| Blue Polo Shirt - Mens       | 217683  |
| Grey Fashion Jacket - Womens | 209304  |
| White Tee Shirt - Mens       | 152000  |

**2. What is the total quantity, revenue and discount for each segment?** 

![a11](https://user-images.githubusercontent.com/130475600/235805727-2d98eed4-8ac1-4f17-83c7-6f9ef6a84da8.PNG)

| segment_name | t_quantity | t_revenue | t_discount |
| ------------ | ---------- | --------- | ---------- |
| Shirt        | 11265      | 406143    | 49594      |
| Jacket       | 11385      | 366983    | 44277      |
| Socks        | 11217      | 307977    | 37013      |
| Jeans        | 11349      | 208350    | 25343      |

**3. What is the top selling product for each segment?

![a12](https://user-images.githubusercontent.com/130475600/235806741-5241fa56-cd78-4d00-b548-b9ef49d2a6af.PNG)

| segment_name | product_id | product_name                     | product_quantity |
| ------------ | ---------- | -------------------------------- | ---------------- |
| Jacket       | 9ec847     | Grey Fashion Jacket - Womens     | 3876             |
| Jeans        | c4a632     | Navy Oversized Jeans - Womens    | 3856             |
| Shirt        | 2a2353     | Blue Polo Shirt - Mens           | 3819             |
| Shirt        | 5d267b     | White Tee Shirt - Mens           | 3800             |
| Socks        | f084eb     | Navy Solid Socks - Mens          | 3792             |
| Jeans        | e83aa3     | Black Straight Jeans - Womens    | 3786             |
| Socks        | 2feb6b     | Pink Fluro Polkadot Socks - Mens | 3770             |
| Jacket       | 72f5d4     | Indigo Rain Jacket - Womens      | 3757             |
| Jacket       | d5e9a6     | Khaki Suit Jacket - Womens       | 3752             |
| Jeans        | e31d39     | Cream Relaxed Jeans - Womens     | 3707             |
| Socks        | b9a74d     | White Striped Socks - Mens       | 3655             |
| Shirt        | c8d436     | Teal Button Up Shirt - Mens      | 3646             |

**4. What is the total quantity, revenue and discount for each category?**

![a13](https://user-images.githubusercontent.com/130475600/235807613-b05cc7e4-8e58-44f1-8d3f-4d1bdef68fe7.PNG)

| category_name | l_quantity | t_revenue | t_discount |
| ------------- | ---------- | --------- | ---------- |
| Mens          | 22482      | 714120    | 86607      |
| Womens        | 22734      | 575333    | 69621      |

**5. What is the top selling product for each category?**

![a14](https://user-images.githubusercontent.com/130475600/235940031-f6f9b367-e6be-454b-91be-33334ab5cb44.PNG)

| category_name | product_name                     | product_id | t_sales |
| ------------- | -------------------------------- | ---------- | ------- |
| Womens        | Grey Fashion Jacket - Womens     | 9ec847     | 3876    |
| Womens        | Navy Oversized Jeans - Womens    | c4a632     | 3856    |
| Mens          | Blue Polo Shirt - Mens           | 2a2353     | 3819    |
| Mens          | White Tee Shirt - Mens           | 5d267b     | 3800    |
| Mens          | Navy Solid Socks - Mens          | f084eb     | 3792    |
| Womens        | Black Straight Jeans - Womens    | e83aa3     | 3786    |
| Mens          | Pink Fluro Polkadot Socks - Mens | 2feb6b     | 3770    |
| Womens        | Indigo Rain Jacket - Womens      | 72f5d4     | 3757    |
| Womens        | Khaki Suit Jacket - Womens       | d5e9a6     | 3752    |
| Womens        | Cream Relaxed Jeans - Womens     | e31d39     | 3707    |
| Mens          | White Striped Socks - Mens       | b9a74d     | 3655    |
| Mens          | Teal Button Up Shirt - Mens      | c8d436     | 3646    |

**6. What is the percentage split of revenue by product for each segment?**

![a15](https://user-images.githubusercontent.com/130475600/235943332-5818ccf2-8e10-4eb2-ae1a-21fa4b9ab475.PNG)

| segment_name | product_name                     | segment_percentage |
| ------------ | -------------------------------- | ------------------ |
| Jacket       | Grey Fashion Jacket - Womens     | 57.03              |
| Jacket       | Khaki Suit Jacket - Womens       | 23.51              |
| Jacket       | Indigo Rain Jacket - Womens      | 19.45              |
| Jeans        | Black Straight Jeans - Womens    | 58.15              |
| Jeans        | Navy Oversized Jeans - Womens    | 24.06              |
| Jeans        | Cream Relaxed Jeans - Womens     | 17.79              |
| Shirt        | Blue Polo Shirt - Mens           | 53.60              |
| Shirt        | White Tee Shirt - Mens           | 37.43              |
| Shirt        | Teal Button Up Shirt - Mens      | 8.98               |
| Socks        | Navy Solid Socks - Mens          | 44.33              |
| Socks        | Pink Fluro Polkadot Socks - Mens | 35.50              |
| Socks        | White Striped Socks - Mens       | 20.18              |

**7. What is the percentage split of revenue by segment for each category?**

![a16](https://user-images.githubusercontent.com/130475600/235944334-9686a28a-3c81-4a0f-b7e1-9b046c24cf79.PNG)

| category_name | segment_name | cat_percentage |
| ------------- | ------------ | -------------- |
| Mens          | Shirt        | 56.87          |
| Mens          | Socks        | 43.13          |
| Womens        | Jacket       | 63.79          |
| Womens        | Jeans        | 36.21          |

**8. What is the percentage split of total revenue by category?** 

![a17](https://user-images.githubusercontent.com/130475600/235947179-3a25b84f-118f-4c49-b8b0-fe56e9e9aae4.PNG)

| first_category | second_category |
| -------------- | --------------- |
| 44.00          | 56.00           |

**9. What is the total transaction “penetration” for each product? (hint: penetration = number of transactions where at least 1 quantity of a product was purchased divided by total number of transactions)**

![a18](https://user-images.githubusercontent.com/130475600/235956506-29fb2645-e72f-4f23-9feb-2be7c0a3d2bb.PNG)


