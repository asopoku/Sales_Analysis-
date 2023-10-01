# Project Overview
This project aims at providing insight into the sales performance of a hypothetical supermarket over the years 2021 to 2022 by analyzing various aspect to identify trends and make data driven decisions and get deep understanding of the supermarket’s performance.

# Data Source
The primary data used for the analysis is supermarket.xlsx sourced from [this website.](https://leanexcelsolutions.com/sales-dashboard-in-excel-power-bi/)

# Tools Used
For this analysis, Microsoft Excel was used for cleaning, mining, analyzing and visualizing using power query, pivot tables and pivot charts

# Data Preparation
The data was prepared for analysis and it was ensured the data was clean by;
- loading and inspecting the data 
- deleting all duplicated entries
- formatting the data into the appropriate types, (ensuring dates are in date formats, texts are in proper format and all unnecessary spaces and special characters are remove  and numbers are in numbers format)
- replacing missing values

# Exploratory Data Analysis (EDA)
- The data was further explore to answer the following questions 
- What was the overall sales for  each year?
- What was the sales made each month and each day?
- What was the total profit made each year?
- What was the profits made each month and profit % made?
- What was the total sales by Sales Type (Direct Sales, Online and Wholesaler)?
- What was the total sales by Payment Method (Cash and Online)?
- What was the total sales by Product Category (Category1 – Category5)?
- What is the top selling product and what is the top selling category?

# Data Analysis
- To find the profit made by the supermarket, new columns such as Total Selling Value (Revenue) was calculated by multiplying Quantity sold by Selling Price and Total Buying Value (Cost) was calculated by multiplying Quantity bought  by the Buying Price.
- The profit was then computed by finding the difference between the Total Selling Value column and Total Buying Value column
- Pivot tables were then created for further and analysis in attempt to answer the questions asked.
- Pivot Charts were then created for Dashboard and Reporting my findings.

# Results & Findings
-  After the analysis, it was found that, 
the Total Sales was $401,412 while Total Profit was $68,908 with Profit% of 21%.
- The Top Selling Product throughout 2021-2022 was Product41 with Total Sales of $22,952  and the Product Category was Category04 with Total Sales of $95,269.
- January recorded most Sales with Total Sales of $41,347 while  April recorded the least Sales with Total Sales of $26,579
- January recorded most Profit with Total Profit of $7,058 while May recorded the least with Total Profit of $4,384

# Dashboard
![Dashboard Excel](https://github.com/asopoku/Sales_Analysis-/assets/72577156/772ccc66-9d38-4c84-83ea-4e017c1c3a42)


# Recommendation
From the findings, it is recommended that;
- the supermarket keep more stocks of Product41 which was seen to have recorded the top selling product.
- also, the supermarket must keep more stocks of products that are in Category04 since it was the top selling category.
- since the highest sales occur in January, it is recommended more stocks of Product41 and items in Category04 are made available in the month of January. This could be as a result of the New Year celebration.
- with 52% of sales occurring in Direct Sales, most of the stocks should be available in the supermarket than the wholesaler since that contributed to only 15% of the total sales.
