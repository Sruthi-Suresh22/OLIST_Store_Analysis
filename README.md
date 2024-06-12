# OLIST STORE ANALYSIS

## Project Description

- Olist is an e-commerce company based in Brazil.
- The Olist Store Analysis project aims to analyze customer purchasing patterns and payment statistics on an E-commerce platform, Olist.
- This project covers several key performance indicators (KPIs) such as weekday vs weekend sales, payment statistics, delivery time, and customer behavior.
- The analysis is based on nine CSV files, which are cleaned and manipulated to understand the e-commerce landscape in Brazil and evaluate the performance of the Olist store, identify trends and extract valuable insights to drive business growth and improve overall efficiency.
- The finding could potentially guide marketing strategies, inventory management, Sellers onboarding & other crucial aspect of the ecommerce business.

## Dataset Details

- Domain : E-Commerce
- Project Name: Olist Store Analysis
- Dataset Name: The Olist dataset comprises 9 seperate datasets, all of which are stored in CSV format namely:
   - olist_customers_dataset 
   - olist_geolocation_dataset
   - olist_order_items_dataset
   - olist_order_payments_dataset
   - olist_order_reviews_dataset
   - olist_orders_dataset
   - olist_products_dataset
   - olist_sellers_dataset
   - product_category_name_translation
- Dataset Type: CSV Data
- Dataset Zip Folder Size: 45 MB
- Data Schema:
  ![Joins](https://github.com/Sruthi-Suresh22/OLIST_Store_Analysis/assets/162356465/aa6ac411-b59d-4b7b-8373-965e9ec47e59)

## KPI's

- Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics
- Number of Orders with review score 5 and payment type as credit card
- Average number of days taken for order_delivered_customer_date for pet_shop
- Average price and payment values from customers of sao paulo city
- Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores

## Excel Dashboard

![Capture](https://github.com/Sruthi-Suresh22/OLIST_Store_Analysis/assets/162356465/a9132e41-457a-4e6d-b3d3-03cddbbf4d81)

## Power BI Dashboard

![Olist Power BI dashboard](https://github.com/Sruthi-Suresh22/OLIST_Store_Analysis/assets/162356465/01cea9f5-50fd-4ffb-9ab0-73b3c97206d0)

## Insights

### KPI-1 : Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics

- The analysis helps in understanding of the buying behavior of customers.
- The analysis of this KPI can help Olist to improve their weekend sales and plan promotions accordingly.
- Higher customer engagement and increased order activity on weekday as compared to weekend could be due to customers having more free time, relaxed schedules, and the opportunity to browse and make purchases at their leisure.
- Promotions, discounts, and advertising campaigns can be strategically planned and tailored to maximize customer engagement and drive sales during specific days of the week.

### KPI-2 : Number of Orders with review score 5 and payment type as credit card

- This KPI helps in understanding customer satisfaction levels and payment preferences. Olist can use this information to identify satisfied customers and encourage them to make repeat purchases.
- Based on review scores customer has reviewed as 5 for around 44k transactions done via credit card. This means customers have been experiencing good experience while doing transaction via credit card.
- Customers who make more orders using a credit card may have a higher level of satisfaction and often signifies a level of trust and convenience and may leave positive reviews, overall shopping experience, leading to higher review score.

### KPI-3 : Average number of days taken for order_delivered_customer_date for pet_shop

- It helps Olist in identifying areas where they can improve their delivery time and maintain customer satisfaction.
- Average calculation shows that shipping takes 11 days.
- Olist store should focus on reducing the shipping days by enhancing the delivery procedure by increasing warehouses for various product and has to recruit more staffs.

### KPI-4 : Average price and payment values from customers of Sao Paulo city

- Sao Paulo City is one of the most popular city of Brazil.Accordingly, we can advise that this city is a profitable city to invest in.
- Olist have correctly worked on its pricing strategy and need to focus more on bringing competitive prices to sustain in long run.
- The higher average price and payment values in Sao Paulo City imply that the customer base in this city may have a higher income level or overall purchasing capacity.
- This helps in understanding the spending patterns of customers in this region. It also helps Olist in identifying high-value customers and creating targeted marketing campaigns.

### KPI-5 : Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.

- This KPI analyzes the relationship between shipping days and review scores. 
- It helps in understanding the impact of delivery time on customer satisfaction levels. 
- Olist can use this information to optimize their logistics and improve their delivery time.
 
## Challenges Faced & Recommendations

- The dataset had the following quality issues : Null & Empty values, Unwanted special characters, Irrelevant columns, Errors in spelling.
- For Olist to maximize sales performance, profitability, and customer satisfaction, the company will need to carefully employ different pricing strategies.
- Olist needs to employ loyalty programs to help improve customer retention rates.
- Olist will have to capitalize on this by putting positive customer feedback on its platform to help attract new and potential customers.
- Olist must prioritize states like Sao Paolo and Rio de Janeiro by offering sales discounts, free shipping, and returns.

## Conclusion

- The Olist Store Analysis project provides valuable insights into customer behavior and payment statistics.
- The analysis of these KPIs helps Olist in identifying areas of improvement and creating targeted marketing campaigns.
- This project serves as a great example of how data analysis can help businesses make informed decisions.
