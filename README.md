# Sales-and-Customer-Analysis-Dashboard (Excel)
![Dashboard](https://github.com/user-attachments/assets/4bef08cb-a6ff-4d98-9403-7f190ea179f3)

**🛍️ E-Commerce Apparel Purchase Dataset**

This dataset contains 28,472 detailed transaction-level records of apparel purchases made on popular Indian e-commerce platforms. It captures customer demographics, product details, sales channels, and shipping information, making it valuable for customer behavior analysis, market segmentation, and sales forecasting.
| **Column Name**    | **Description**                                                                                            |
| ------------------ | ---------------------------------------------------------------------------------------------------------- |
| `Index`            | Serial number for each record.                                                                             |
| `Order ID`         | Unique identifier for the order, includes platform and sub-order metadata.                                 |
| `Cust ID`          | Unique identifier for the customer.                                                                        |
| `Gender`           | Gender of the customer – `Women`, `Men`.                                                                   |
| `Age`              | Age of the customer (ranging from 18 to 78).                                                               |
| `Age Group`        | Age segmentation – `Teenager`, `Adult`, `Senior`.                                                          |
| `Date`             | Date of purchase (format: DD-MM-YYYY).                                                                     |
| `Month`            | Month of the order                                                               |
| `Status`           | Order status – `Delivered`, `Cancelled`, `Refunded`, `Returned`.                                           |
| `Channel`          | Platform used – `Ajio`, `Amazon`, `Flipkart`, `Meesho`, `Myntra`, `Nally`, `Others`.                       |
| `SKU`              | Product code (Stock Keeping Unit) identifying specific item variant.                                       |
| `Category`         | Type of product – `Blouse`, `Bottommen`, `Ethnic Dress`, `Kurta`, `Saree`, `Set`, `Tops`, `Western Dress`. |
| `Size`             | Size of the product – `XS`, `S`, `M`, `L`, `XL`, `XXL`, `3XL`, `4XL`, `5XL`, `6XL`, `Medium`, `Free`.      |
| `Qty`              | Quantity ordered (ranges from 1 to 5).                                                                     |
| `Amount`           | Purchase amount in INR .                                                                    |
| `ship-city`        | City to which the order was shipped.                                                                       |
| `ship-state`       | Indian state for shipping .                                                   |
| `ship-postal-code` | Indian postal (PIN) code.                                                                                  |
| `ship-country`     | Country code – typically `IN` (India).                                                                     |
| `B2B`              | Boolean value indicating if the order is Business-to-Business – `TRUE` or `FALSE`.                         |

**✅ Charts and Their Insights:**

🟦 Order Status Chart

➤ Shows the count of orders based on status: Delivered, Cancelled, Refunded, and Returned.

🟩 Sales and Order by Platform Chart

➤ Compares total sales amount and number of orders across different e-commerce platforms like Amazon, Flipkart, Meesho, etc.

🟧 Monthly Sales Chart

➤ Displays total sales for each month, helping identify high and low-performing months.

🟪 Age Group Donut Chart

➤ Shows customer distribution across different age groups: Teenager, Adult, and Senior.

🟨 Top 10 States (Map)

➤ Highlights the states with the highest number of orders using a geographical map.

🟥 Size and Quantity Line Chart

➤ Illustrates which product sizes are most frequently ordered in terms of quantity.

🟫 Category vs Sales Line Chart

➤ Shows total sales amount for each product category such as Tops, Saree, Kurta, etc.

🟦 Category vs Order Bar Chart

➤ Displays the number of orders placed for each product category.

**STORY**

Welcome to Sales and Customer Analysis Dashboard, a visual narrative of how customers engage with fashion across India's booming e-commerce platforms.

As we begin our exploration, we immediately notice the total sales value reaching an impressive ₹1.95 Crores — a testament to the growing influence of online apparel shopping. This performance is driven by over 28,000 unique orders and a nearly equal number of shipped items, indicating a healthy and responsive order pipeline.

Moving to the Order Status, the majority of orders are delivered successfully, reflecting strong fulfillment capabilities. A smaller portion accounts for cancellations, returns, and refunds, which is typical in the online retail space, yet worth monitoring for quality and service improvements.

Our attention then shifts to platform performance. Here, we see that Meesho, Flipkart, and Amazon emerge as top players in terms of both sales revenue and order volume. These platforms are not just distribution channels — they’re powerful ecosystems influencing consumer decisions at scale.

Zooming into the monthly sales trends, we observe distinct peaks — likely aligned with seasonal sales or festive campaigns — that help us identify the most impactful sales periods. This pattern enables us to strategize marketing efforts and inventory planning with precision.

Next, we examine our customer demographics. A large share of purchases come from adult women, particularly those aged 25–45, indicating a prime audience segment. This insight empowers targeted advertising and product design.

Geographically, the top 10 states by order volume reveal strong engagement from regions like Maharashtra, Karnataka, and Delhi, guiding us toward region-specific promotions and optimizing our logistics.

Understanding customer preferences further, we analyze size vs. quantity ordered. The most frequently purchased sizes include Medium, Large, and Free Size, reflecting prevalent body types or stocking patterns.

We then dive into product category performance. Categories such as Sarees, Tops, and Western Dresses dominate both in revenue and order count, suggesting clear product preferences. This knowledge helps in refining our catalog and focusing on what sells best.

Finally, the dashboard ties everything together with interactive filters — by gender, age group, platform, product category, and month — allowing for dynamic exploration of trends and drill-down analysis.

This dashboard isn't just a report — it's a story of consumer choices, market dynamics, and business performance. It serves as a strategic tool for decision-makers to identify opportunities, reduce inefficiencies, and grow smarter in the competitive world of online fashion retail.
