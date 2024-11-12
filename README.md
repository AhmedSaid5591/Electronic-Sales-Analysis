# Electronic-Sales-Analysis
Project implemented by Ahmed Said Ahmed.
# Table of Contents
  1. [Introduction](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#introduction)
  2. [Tools](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#introduction)
  3. [Data Card](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#introduction)
  4. [Data Processing](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#data-processing)
  5. [Data modeling](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#data-modeling)
  6. [Data Visualization](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#data-visualization)
  7. [Contributions](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#contributions)
  8. [Contact Information](https://github.com/AhmedSaid5591/Electronic-Sales-Analysis/edit/main/README.md#contact-information)

# Introduction
This project provides a comprehensive analysis of the sales of an electronics store, customer purchasing behavior, and growth rate in the period from September 2023 to September 2024. This analysis was implemented to monitor the store's performance and solve problems if any, improve the level of growth in sales through clear visions in the report and conclusions from the performance keys.
# Tools
  1. Python (data processing)
  2. Power BI (data modeling , data visualization)
# Data Card
![Screenshot 2024-11-12 143825](https://github.com/user-attachments/assets/01097934-b59a-4c72-8674-43be1c448f87)
  ## Description:
  This dataset contains sales transaction records for an electronics company over a one-year period, spanning from September 2023 to September 2024. It includes detailed information about customer demographics,     product types, and purchase behaviors.

  ## Key Features:

  * Customer ID: Unique identifier for each customer.
  * Age: Age of the customer (numeric)
  * Gender: Gender of the customer (Male or Female)
  * Loyalty Member: (Yes/No) (Values change by time, so pay attention to who cancelled and who signed up)
  * Product Type: Type of electronic product sold (e.g., Smartphone, Laptop, Tablet)
  * SKU: a unique code for each product.
  * Rating: Customer rating of the product (1-5 stars) (Should have no Null Ratings)
  * Order Status: Status of the order (Completed, Cancelled)
  * Payment Method: Method used for payment (e.g., Cash, Credit Card, Paypal)
  * Total Price: Total price of the transaction (numeric)
  * Unit Price: Price per unit of the product (numeric)
  * Quantity: Number of units purchased (numeric)
  * Purchase Date: Date of the purchase (format: YYYY-MM-DD)
  * Shipping Type: Type of shipping chosen (e.g., Standard, Overnight, Express)
  * Add-ons Purchased: List of any additional items purchased (e.g., Accessories, Extended Warranty)
  * Add-on Total: Total price of add-ons purchased (numeric)
    

  ## Data Stats:

  * Total Rows: 20,000
  * Time Period: September 2023 to September 2024
  * Product Types: Includes various electronics such as Smartphones, Laptops, Tablets, and Smartwatches.


# Data Processing
  * Handle missing values and Replacing certain missing values to maintain data integrity.
  * Removing duplicates to ensure the uniqueness of the dataset.
  * Create some necessary columns to make them primary keys for some entities.
  * Dropping unnecessary columns to streamline the dataset.
  * Uploading the final cleaned data to Power BI for visualization.
    
# Data modeling
  Create Star Schema with determine dimensions:
    ![Screenshot 2024-11-12 145442](https://github.com/user-attachments/assets/099eb686-2145-4f0c-91c2-de629df04628)


# Data Visualization
  Note:The focus will be on the year 2024 because it has more months of data.

  ----------------------------------------------------------------------------------------------------------------
  ![Screenshot 2024-11-10 153306](https://github.com/user-attachments/assets/9996d01a-1b1f-416d-8062-0e26766ad2e9)
  This dashboard provides a comprehensive overview of customer insights and sales analysis for the electronics market between September 2023 and September 2024. Let's break down each section and summarize         potential conclusions:

## 1. Top Metrics (Overall Summary)
  * Total Customers: 11K
  * Returning Customers: 4,519 (around 41% of total customers)
  * New Loyalty Members: 3,314
  * Average Age: 49 years
#### Conclusions:

  * A significant portion of customers are returning, which could indicate good customer retention.
  * The introduction of 3,314 new loyalty members within the year suggests effective loyalty program efforts.
  * The average customer age of 49 years might imply that the products or marketing appeals more to middle-aged customers.

## 2. Customer Demographics (Gender Breakdown)
  * Male: 5,413 (48.95%)
  * Female: 5,645 (51.05%)
#### Conclusions:

  * The gender distribution is nearly balanced, with a slight tilt toward female customers. This balance suggests that the electronics market appeals to both men and women almost equally.

## 3. Loyalty Program Participation
  * Non-Loyalty Members: 3.31K (25.72%)
  * Loyalty Members: 9.57K (74.28%)
#### Conclusions:

  * A large majority of customers are loyalty program members, which indicates the loyalty program's appeal. This could be contributing to the high rate of returning customers.

## 4. Customer Trends Over Time
  * Returning Customers and New Loyalty Members: Trends show a steady increase in returning customers, with occasional fluctuations. New loyalty members appear consistent, though at lower levels than returning      customers.
#### Conclusions:

  * The steady number of returning customers indicates a loyal customer base. The consistency in new loyalty members could suggest either a stable interest or the potential for further engagement strategies to      boost growth.

## 5. Total Order Price by Age and Gender
  * This line chart indicates the total order price segmented by age and gender, with fluctuations across different age groups.
#### Conclusions:

  * The data shows variation in order prices by age and gender, possibly indicating that certain age groups and genders spend more. This insight could be used for targeted marketing and promotion strategies.

## 6. Top 10 Customers by Revenue
  * The treemap highlights the top customers based on revenue, with figures ranging from $27.58K to $35.06K.
#### Conclusions:

  * A small group of top customers contributes a significant portion of revenue, which may indicate a dependency on high-value customers. Efforts to maintain and expand these relationships could be essential        for sustained revenue.

#### Overall Conclusions:
  * The electronics market benefits from a well-established customer base, with a strong retention rate and effective loyalty program.
  * Gender and age are well-distributed among customers, but opportunities may exist to increase spending in specific demographics.
  * Strategies to attract new loyalty members and nurture high-spending customers could further enhance growth and profitability.

This dashboard provides a strong foundation for data-driven decision-making, helping stakeholders focus on customer retention, loyalty program growth, and targeted marketing efforts.

---------------------------------------------------------------------------------------------------------------
![Screenshot 2024-11-11 164216](https://github.com/user-attachments/assets/abc028c7-ee06-4fad-a7e7-8315e195da5c)

This dashboard focuses on sales analysis for the electronics market between September 2023 and September 2024. Here's a breakdown of each section and key insights:

## 1. Top Metrics (Sales Summary)
   * Total Customers: 11K
   * Total Revenue: $57.88M
   * Average Order Price: $3.35K
   * Average Device Price: $596.55
   * Total Transactions: 17K
#### Conclusions:

   * The total revenue of $57.88M from 17,000 transactions indicates a substantial market size.
   * With an average order price of $3.35K and an average device price of $596.55, customers are buying multiple devices or high-value items per transaction.
   * The balance between the number of transactions and total customers suggests that many customers make repeat purchases.

## 2. Order Status
   * Completed Transactions: 11.63K (67.24%)
   * Cancelled Transactions: 5.67K (32.76%)
#### Conclusions:

   * The cancellation rate of nearly 33% is relatively high. This could indicate issues with order processing, customer satisfaction, or supply chain challenges. Reducing cancellations could lead to significant      revenue growth.

## 3. Revenue Trends Over Time
   * The line chart shows monthly revenue trends, peaking at $6.8M between May and July 2024, then gradually declining to $5.1M in September 2024.
#### Conclusions:

   * The drop in revenue after July might be due to seasonal demand variations, market saturation, or economic factors affecting consumer spending. Understanding the causes of this decline could help develop         strategies to stabilize or increase revenue in slower months.

## 4. Product Sales Analysis (SKU Breakdown)
* The table lists product SKUs with metrics such as:

     * Average Total Order Price
     * Average Unit Price
     * Average Rating
     * Sum of Quantity Sold
     * Sum of Add-ons
     * Total Revenue
* Top SKUs by Revenue:

     * SKU1004: $9.88M
     * SKU1003: $6.68M
     * SMP234: $12.62M (highest revenue)
#### Conclusions:

   * High-performing SKUs (e.g., SMP234, SKU1004, SKU1003) contribute significantly to revenue, indicating popular or high-value items.
   * There is a noticeable variance in product ratings, with most around 2.9 to 3.0, which might suggest room for improvement in product quality or customer satisfaction.
   * The "Sum of Add-ons" metric shows additional revenue generated through add-ons, which may represent accessories, warranties, or services sold with the main products.

#### Overall Conclusions:
   * The electronics market is strong, but high cancellation rates and seasonal revenue dips may present challenges.
   * Focusing on reducing cancellations and increasing customer satisfaction could enhance revenue.
   * There is an opportunity to drive add-on sales, particularly for top-performing products, which could further increase average order value and profitability.


This dashboard provides a clear overview of sales performance and customer purchasing behavior, allowing for targeted improvements in product offerings, customer satisfaction, and revenue management.


------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2024-11-11 165017](https://github.com/user-attachments/assets/d6b8b8a1-286e-40e5-aedd-3d94b4b0a0b0)

This section of the dashboard focuses on product-specific metrics in the electronics market for the period from September 2023 to September 2024, providing insights into product quantity, transactions, and trends over time.

## 1. Top Metrics (Product Overview)
  * Total Customers: 11,000
  * Average Rating: 3.08
  * Average Order Price: $3.35K
  * Average Device Price: $596.55
#### Conclusions:

  * The average order price is relatively high, which may indicate that customers are purchasing multiple products per transaction or high-value items. However, the average rating is only 3.08, suggesting           moderate customer satisfaction that could be improved.'

## 2. Total Quantity by SKU
* Top products by quantity sold:
    * TBL345: 11.3K units
    * HDP456: 11.2K units
    * SWT567: 11.1K units
    * SMP234: 10.8K units
* Other SKUs range between 7.6K to 8.2K units.
#### Conclusions:

  * TBL345 and HDP456 are the best-selling products by quantity, indicating strong market demand for these items. This high quantity sold suggests they may be popular products due to pricing, quality, or customer preference. The lower-quantity SKUs might represent specialized or premium items or those with limited appeal.

## 3. Total Transaction by SKU
* Top SKUs by Transaction Count:
  * TBL345: 2,062 transactions
  * HDP456: 2,010 transactions
  * SMP234: 1,987 transactions
* Other SKUs have around 1,400 to 1,600 transactions.
#### Conclusions:

  * TBL345 and HDP456 also lead in transaction counts, reinforcing that these items are not only sold in high quantities but are frequently part of customer transactions. SKUs with fewer transactions but high quantities may indicate bulk purchases or orders from larger clients.

## 4. Quantity Trends by Year and SKU
  * The line chart shows fluctuations in SKU quantities over the months from September 2023 to September 2024. While quantities vary across SKUs, there is a noticeable decline in early 2024.
#### Conclusions:

  * Seasonal trends appear, with several peaks and valleys, suggesting fluctuating demand throughout the year. For instance, spikes in late 2023 could align with holiday season demand, while a decline in early 2024 indicates a typical post-holiday drop. Monitoring these trends helps in planning for production and inventory to match demand cycles effectively.

#### Overall Conclusions:
  * Products TBL345 and HDP456 are strong performers both in terms of quantity sold and transaction count, which makes them essential items in the electronics portfolio.
  * The moderate average rating (3.08) suggests room for improvement in customer satisfaction, potentially by addressing common product or service issues.
  * Seasonal and monthly quantity fluctuations emphasize the need for dynamic inventory and marketing strategies to capture peak demand periods and manage slowdowns.


This product-focused dashboard provides valuable insights to prioritize high-performing items, address customer satisfaction, and adjust for seasonality in sales and inventory.



--------------------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2024-11-11 170058](https://github.com/user-attachments/assets/4b4630c2-470c-4c5e-b588-41c7027a4c25)

This section of the dashboard provides insights into customer behavior for the electronics market from September 2023 to September 2024. Key metrics and visualizations here cover payment methods, shipping types, add-on orders, order status, and order ratings.

## 1. Top Metrics (Behavior Overview)
  * Total Customers: 12,000
  * Average Quantity per Order: 5
  * Average Add-On Revenue per Order: $82.27
  * Average Age: 49
#### Conclusions:

  * With an average quantity of 5 per order, customers are purchasing multiple items, which could indicate bundled deals or a tendency to buy several products in one transaction.
  * The average add-on revenue per order of $82.27 suggests that add-ons or additional items contribute significantly to revenue, highlighting the importance of cross-selling and upselling strategies.
  * An average customer age of 49 suggests the customer base skews towards middle-aged individuals, which may influence product selection, marketing, and user experience.

## 2. Payment Method Distribution
  * Credit Card: 29.34%
  * PayPal: 28.99%
  * Bank Transfer: 16.86%
  * Cash: 12.46%
  * Debit Card: 12.36%
#### Conclusions:

  * Credit cards and PayPal are the most popular payment methods, together accounting for more than 58% of transactions. This indicates that the majority of customers prefer electronic payments, although a notable portion still uses bank transfers and cash.
  * A diverse mix of payment methods can cater to customer preferences, but increasing digital payment options could streamline transactions and reduce handling costs associated with cash.

## 3. Shipping Type
  * Standard: Most popular option, with over 6,000 orders.
  * Other options (Express, Overnight, Same Day, Expedited) have around 2,000 to 2,500 orders each.
#### Conclusions:

  * The high use of standard shipping reflects customer cost-consciousness or willingness to wait for deliveries.
  * Although other shipping methods (like express and same-day) are used, they are less popular, possibly due to additional costs. Offering incentives for faster shipping or highlighting delivery speed in promotions could increase adoption of premium shipping options.

## 4. Orders by Add-On Inclusion
  * Add-On Included: 75.66%
  * No Add-On: 24.34%
#### Conclusions:

  * The majority of orders (75.66%) include add-ons, which aligns with the high average add-on revenue per order. This success in add-ons suggests effective cross-selling practices or customer inclination toward add-ons that enhance the core product.
  * The add-on strategy is a revenue driver, so continuing to offer relevant add-ons could further boost sales.

## 5. Order Status
  * Completed Orders: Over 10,000
  * Cancelled Orders: Around 5,000
#### Conclusions:

  * A high cancellation rate (approximately one-third of total orders) could indicate issues with product availability, order processing, or customer dissatisfaction. Investigating common causes of cancellation and addressing them could improve completion rates.

## 6. Orders Rating
  * The majority of orders have high ratings, with 7,960 rated at the top level, while lower ratings (down to level 2) have progressively fewer orders.
#### Conclusions:

  * Most orders are rated highly, indicating general customer satisfaction. However, a notable portion has ratings below the top level, suggesting some room for improvement. Analyzing feedback associated with lower ratings could provide insights for enhancing customer satisfaction.

#### Overall Conclusions:
  * High Engagement with Add-Ons: With 75.66% of orders including add-ons and an average add-on revenue of $82.27, add-ons significantly enhance revenue. Maintaining a strong selection of add-ons and strategically marketing them could further increase this benefit.
  * Preference for Standard Shipping: The prevalence of standard shipping highlights customer cost sensitivity. Offering competitive shipping options or promotions could encourage more customers to opt for faster methods.
  * Payment Method Flexibility: The popularity of credit card and PayPal payments reflects a modern, digitally enabled customer base, though other methods like cash are still used. Expanding electronic payment options may further streamline the process.
  * Customer Satisfaction but Some Cancellation Issues: High order ratings suggest overall satisfaction, but a notable cancellation rate indicates areas for improvement in the customer journey or order fulfillment.


This dashboard section effectively captures behavioral insights, providing direction for optimizing payment, shipping, and add-on strategies, as well as opportunities for reducing cancellations and enhancing customer satisfaction.

-----------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2024-11-11 171627](https://github.com/user-attachments/assets/22ca9c39-f194-4760-9be5-7299a9d738f1)
This section of the dashboard provides insights into the seasonal trends and customer loyalty within the electronics market from September 2023 to September 2024. Key metrics and visualizations here include transactions on peak days, revenue trends, loyalty membership, order status over time, and SKU quantities by year.

## 1. Top Metrics (Seasonal Overview)
  * Total Customers: 11,000
  * Returning Customers: 4,519
  * New Loyalty Members: 3,314
  * Total Revenue: $57.88 million
#### Conclusions:

  * Nearly 41% of the customer base (4,519 out of 11,000) are returning customers, suggesting a strong repeat customer rate and a level of customer loyalty that can be leveraged for upselling and retention strategies.
  * The addition of 3,314 new loyalty members indicates successful customer acquisition efforts. This could lead to higher retention and increased future spending from these customers.

## 2. Top 5 Days by Transactions
  * The chart shows the top 5 days with the highest transaction volumes, with each of these days having over 600 transactions.
#### Conclusions:

  * Peak transaction days could be associated with special promotions, sales events, or product launches. Identifying these peak days provides insights into the effectiveness of marketing campaigns and customer behavior during promotional events.
  * Planning future promotions around similar times or replicating successful campaigns on these dates could help maximize sales.

## 3. Revenue by Year & Month
  * Revenue appears relatively steady from August through March, but there is a notable decline starting in April and dropping significantly in September.
#### Conclusions:

  * The drop in revenue in the later months may indicate a seasonal slowdown, changes in demand, or possibly market saturation.
  * Understanding this trend can help in planning marketing strategies and inventory management to counteract slower periods. Consider ramping up promotions or new product introductions during low-revenue months to offset the downturn.

## 4. Order Status by Year
  * The chart shows completed and canceled orders over time, with a fairly consistent level of completed orders and a lower, relatively steady rate of cancellations.
#### Conclusions:

  * The steady completion rate is a positive indicator of customer satisfaction and operational efficiency, while the consistent cancellation rate suggests there may still be some areas to improve in customer service or order fulfillment.
  * Focusing on reducing the cancellation rate could potentially increase revenue. This might involve analyzing reasons for cancellations and addressing any recurring issues in product availability, delivery times, or customer service.

## 5. Quantity of SKU by Year
  * This line chart shows the quantities sold for different SKUs across the year, with a general pattern of fluctuation and a decline toward the end of the period.
#### Conclusions:

  * The downward trend in SKU quantities toward the end of the period aligns with the revenue drop observed in the "Revenue by Year & Month" section, suggesting reduced customer demand or purchasing behavior.
  * Certain SKUs may experience cyclical demand, so focusing on optimizing inventory and promotions for high-demand SKUs during peak periods could help balance inventory and improve sales in slower periods.

#### Overall Conclusions:
  * Strong Customer Retention and Loyalty: With a substantial number of returning customers and new loyalty members, the business benefits from a solid foundation of loyal customers. Continuing to engage with loyalty programs and targeting repeat buyers could further strengthen customer retention.
  * Seasonal Revenue Decline: The decrease in revenue and SKU quantity toward the end of the period indicates a need for targeted strategies to combat seasonal slumps. Implementing strategic promotions, holiday campaigns, or product launches in these slower months could help stabilize revenue.
  * Peak Sales Days Optimization: The insight into top transaction days reveals opportunities to maximize sales around these periods through timely promotions and ensuring sufficient inventory.
  * Opportunity to Reduce Cancellations: Although order completions are high, maintaining a focus on reducing cancellations through better order management and customer service could contribute positively to revenue and customer satisfaction.


This seasonal dashboard provides valuable insights into customer loyalty, sales trends, and operational performance, supporting data-driven decision-making to optimize future sales strategies.


# Contributions
We welcome contributions to this project. If you have suggestions or improvements, please reach out to us.

# Contact Information
For inquiries or further collaboration, please contact us at [memosaid091@gmail.com]
