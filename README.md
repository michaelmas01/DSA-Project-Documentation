# DSA-Project-Documentation
## Amazon Case Study

### Project Overview
The goal of this project is to analyse **Amazon E-Commerce** product data and uncover key business insights using Microsoft Excel. This includes evaluating product pricing, discount patterns, customer reviews, ratings, and revenue potential. The project culminates in the creation of a dashboard that visualises performance trends across categories, helping stakeholders understand consumer behaviour and product success.

### Dataset Summary
- **Source:** Provided Excel dataset (Case Study 1)
- **Total Records:** 1389 (cleaned)
- **Key Columns:** product_id, product_name, category, main_category, actual_price, discounted_price, discount_percentage,   rating, rating_count

### Tools & Techniques Used
Some of the Microsoft Excel tools and techniques used are: 
- PivotTables
- Sort and Filters
- Line and bar charts
- Formulas & Functions: IF, LEFT, FIND 
- Calculated fields: Discount % (Calculated), Discount 50% and more, Potential Revenue, Price Bucket, and Rating + Review Score (Combined Score).

### Analysis Performed
Analysis was performed through the use of pivot tables and calculated columns to answer the following questions:
1.	What is the average discount percentage by product category?
2.	How many products are listed under each category?
3.	What is the total number of reviews per category?
4.	Which products have the highest average ratings?
5.	What is the average actual price vs the discounted price by category?
6.	Which products have the highest number of reviews?
7.	How many products have a discount of 50% or more?
8.	What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
9.	What is the total potential revenue (actual_price × rating_count) by category?
10.	What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
11.	How does the rating relate to the level of discount?
12.	How many products have fewer than 1,000 reviews?
13.	Which categories have products with the highest discounts?
14.	Identify the top 5 products in terms of rating and number of reviews combined.

### Chart Presentation
![Pie Chart - Average Discount %](https://github.com/user-attachments/assets/679dc007-02c3-4d0f-a234-df136708a686)
![Bar Chart - Ratings](https://github.com/user-attachments/assets/f22e9f1e-7d26-46c8-811e-0ad6ba756871)
![Bar Chart - Top 3 Reviews](https://github.com/user-attachments/assets/cccad8a2-fd1f-4c75-8143-0d9d04d4cb79)
![Combo Chart - Average Actual Price VS Discounted Price](https://github.com/user-attachments/assets/e71470d3-21ff-41a9-934e-aa798a7eb33f)
![Line Chart - Unique Product VS Price Bucket](https://github.com/user-attachments/assets/1d62cc4a-49e2-43d4-8d67-1637c94f1359)
![Scatter Chart - Discount % VS Rating](https://github.com/user-attachments/assets/6df845fa-015e-4123-b294-93170388a998)


### Key Business Insights
1.	**High Discounts in Key Segments:** “HomeImprovement” and “Computers\&Accessories” offer the highest average discounts (above 50%), suggesting highly competitive or promotional product segments.
2.	**Product Concentration in Tech:** “Computers\&Accessories” hosts the highest number of products, showing a clear focus on tech accessories and peripherals.
3.	**High Customer Engagement in Electronics:**  “Electronics” and “Home\&Kitchen” lead in review volume, indicating strong customer interest and possibly higher sales volume.
4.	**Top Products by Engagement:**  Products like “AmazonBasics HDMI Cables” and “boAt earphones” top the charts in both rating and number of reviews, proving high market trust and popularity.
5.	**Affordable Pricing Strategy:** A majority of products are priced between ₹200–₹500, reflecting a value-conscious market trend.
6.	**Discount Doesn’t Affect Rating Much:** Customer satisfaction (ratings) remains relatively stable across different discount levels, implying discounting does not degrade perceived value.
7.	**Revenue Drivers:** Products with high price + high reviews (like premium electronics and kitchen devices) drive the most potential revenue.

### Dashboard Overview
The final Excel dashboard summarizes all major insights using:
1.	PivotTables for breakdowns by category, discount level, and pricing
2.	Charts for rating trends vs. discount buckets
3.	Highlight tables for top-performing products by review count and rating
4.	Summary metrics like:
    - Number of products by discount range
    - Product count by price range
    - Total revenue potential by category

![Dashboard](https://github.com/user-attachments/assets/169047d0-d9e6-4c99-9541-0bcc4a684c96)

Each analysis task is placed in its own worksheet, with a unified **Dashboard** sheet presenting the visuals and KPIs in a clean, interactive layout.

### Conclusion
This case study demonstrates practical skills in data cleaning, transformation, visualization, and business insight generation using Excel. The combination of technical analysis and strategic insight lays the foundation for further work in retail analytics, marketing, or business intelligence roles.

