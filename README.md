# Office-Supplies-Sales-Analyst
This project analyzes office supplies sales data to identify sales trends, customer behavior, product performance, and business opportunities. The objective is to generate actionable insights that help improve sales performance and support data-driven decision-making.
## Business Problem
Although the company generated $55,774 in total sales, monthly sales fluctuate considerably, making it challenging to achieve consistent revenue growth and effectively plan inventory and marketing strategies.
## Questions (KPIs)
- Why do sales fluctuate each month?
- List top 10 products have the highest sales?
- Which categories products generate the highest sales?
- List top 10 cities have the highest sales?
- Which segment contributes the most?
- Which shipping method is most frequently used?
## Tools Used
- Microsoft Excel: initial data inspection, calculation, quality checks
- Pivot Tables: aggregations, summaries, insight
- Tableau: interactive dashboard, key indicators visualization
- GitHub: repository management, version control (Git), project documentation (README), and portfolio publishing
## Dataset
The dataset used in this project including:
| Feature                         | Description                                                     |
| ------------------------------- | --------------------------------------------------------------- |
| Order ID                        | Unique identifier for each sales transaction.                   |
| Order Date                      | Date when the order was placed.                                 |
| Ship Date                       | Date when the order was shipped.                                |
| Ship Mode                       | Shipping method used for the order.                             |
| Customer ID                     | Unique identifier for each customer.                            |
| Customer Name                   | Name of the customer.                                           |
| Segment                         | Customer segment (e.g., Consumer, Corporate, Home Office).      |
| Country / City / State / Region | Customer's geographic location.                                 |
| Product ID                      | Unique identifier for each product.                             |
| Category                        | Main product category (Office Supplies, Furniture, Technology). |
| Sub-Category                    | Product subcategory (e.g., Appliances, Art, Binders, Envelopes, Fasteners, Labels, Paper, Storage, Supplies).            |
| Product Name                    | Name of the product sold.                                       |
| Sales                           | Revenue generated from each transaction.                        |
| Quantity                        | Number of units sold.                                           |
| Discount                        | Discount applied to the transaction.                            |
| Profit                          | Profit earned from the transaction.                             |

## Process
- Verify data for any missing values and anomalies, and sort out the same
- Made sure data is consistent and clean with respect to data type, data format, and values used
- Created Pivot tables according to the question asked
- Merge all pivot tables into one dashboard and apply slicer to make dynamic
## Dashboard
<img width="322" height="176" alt="Dashboard Office Supplies Sales (Excel)" src="https://github.com/user-attachments/assets/ee308864-8bb3-490b-a608-d82654ecb540" />.
## Result
This is result from Office Supplies Sales Analyst
- **Sales Trend Analysis** : The monthly sales trend fluctuates throughout the year, with noticeable peaks and declines.The fluctuations may be influenced by seasonality, promotional activities, or changing customer demand.
- **Regional Performance**: Cities such as New York City, Atlanta, and San Francisco generate the highest sales. And state such as New York, Georgia, and California generate the highest sales
- **Best Selling Category Products**: Storage and Binders category contributes the largest share of sales, while categories such as Envelopes, Labels, and Fasteners contribute much less.
-  **Product Performance**: The Top 10 Products contribute a significant portion of total sales, while many other products generate relatively low sales.
-  **Segment Analysis**: The Consumer segment generated the highest sales, particularly in 2019, but experienced considerable fluctuations over the following years. In contrast, the Corporate segment demonstrated more stable growth, indicating increasing demand from business customers. Meanwhile, the Home Office segment showed inconsistent performance with significant changes across the observed period.
- **Shipping Analysis**: Most customers use Standard Class Shipping representing approximately 61% of all customer shipments. This suggests that customers prioritize cost-effective delivery over speed. Therefore, maintaining the reliability and efficiency of Standard Class should remain a priority.
## Summary of Insight
### Sales Trend
- The company generated $55,774 in total sales, with 1,833 products sold across 240 customers, resulting in $9,039 in total profit.
- Monthly sales fluctuated throughout the year, with several significant peaks and declines, indicating inconsistent customer demand and potential seasonal purchasing patterns.
- Although the business maintained positive sales performance, the fluctuations suggest opportunities to improve sales stability through better demand forecasting and strategic promotional planning.
<p align="center">
<img width="700" height="300" alt="image" src="https://github.com/user-attachments/assets/d28693ca-b5f6-437e-9500-ee80eba01e2a" />

### Product Performance
- Sales were concentrated in a limited number of products, with the Top 10 products contributing the majority of total sales.
- Storage and Binders category contributes the largest share of sales, while categories such as Envelopes, Labels, and Fasteners contribute much less.
- This distribution indicates a strong dependence on a few high-performing products and categories.
<p align="center">
<img width="456" height="274" alt="image" src="https://github.com/user-attachments/assets/02cc7ebc-cd4c-49df-82fe-0bc1e0de55a1" />

### Customer Segments
- The Consumer segment generated the highest sales but showed considerable year-to-year fluctuations.
- The Corporate segment demonstrated more consistent growth, indicating increasing demand from business customers.
- The Home Office segment contributed the smallest share of sales and exhibited inconsistent performance.
<p align="center">
<img width="1127" height="754" alt="Picture2-segment" src="https://github.com/user-attachments/assets/4f9406fa-31ae-4a3c-96f9-7b2a783b3e62" />

### Regional Performance
- The highest sales were recorded in several states, such as New York, Georgia, and California.
- Sales were concentrated in major cities such as New York City, Atlanta, and San Francisco, while many other regions contributed comparatively lower sales.
- The uneven geographic distribution suggests opportunities to expand into underperforming markets.
<p align="center">
<img width="1648" height="913" alt="Picture3-map" src="https://github.com/user-attachments/assets/c915ee35-588b-4b55-adcf-1411537a5c36" />

## Business Recommendation
- Implement **sales forecasting** and prepare a **promotional calendar** to maintain consistent demand throughout the year. This strategy can help more stable monthly sales and improved inventory planning.
- **Promote lower-performing** products through **discounts**, **product bundling**, or **cross-selling**. This approach can encourage customers to purchase a wider range of products, resulting in a more balanced sales distribution and reduced dependence on a few best-selling items.
- **Expand marketing campaigns** and **distribution** to regions with lower sales potential. By reaching underserved markets, the company can broaden its customer base, increase market penetration, and drive overall revenue growth.
- The company should s**trengthen customer retention programs** for the Consumer segment while **expanding partnerships** with businesses, schools, government institutions, and other organizations to capitalize on the growing Corporate market. Additionally, **targeted promotions and bundled product offerings** for Home Office customers can help improve sales consistency across all customer segments.
- **Monitor delivery performance** and **offer faster shipping options** for customers who need them. Improving shipping reliability and flexibility can enhance customer satisfaction, encourage repeat purchases, and strengthen long-term customer loyalty.
