# ChocoFun Sales Report

### Dashboard Link : https://drive.google.com/file/d/1794hsOEXT20Y6H7PcInC2wF-SIN-hkLK/view?usp=sharing

## Problem Statement

This project helps the ChocoFun company better understand how they are performing across various regions and identifies areas for improvement in their sales. The dashboard provides insights into total orders by region, total sales, profit margin, top 5 customers, and more. Its report offers a comprehensive analysis of how they can acquire new customers and increase their sales. It provides an overview of both sales and orders. The report consists of data from the years 2022, 2023, and 2024.

### Steps followed

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2: Cleaned the data using the Power Query Editor. Renamed the column names, adjusted the date formats, and set the appropriate data types for each column before creating the report.

- Step 3:
  It was observed that no errors or empty values were present in any of the columns .

- Step 4:
   I calculated the previous month's sales, profit, and cost using the DAX formula.

- Step 5:
  Visual filters were added for the years 2022, 2023, and 2024. Additionally, filters were applied for different products.

- Step 6:
  Three cards were added to the canvas, representing  profit, orders and sales.

- Step 7:
  A clustered column chart was added to the report dashboard to categorize sales and previous year's sales across different months.


- Sales By Year : 
2022: $7,379,191
2023: $9,609,584
2024: $417,555

Total Sales: 
- The total sales for the three years is $17M.
- Previous month's sales are 16.99M, with a sales variance of 417.56K.
![sales](https://github.com/user-attachments/assets/87b2991a-2e5a-4832-9444-128fe30aa620)

Orders: 
- The total number of orders for the three years is 13K.
- Previous month's orders are 12K, with an order variance of 286.
![order](https://github.com/user-attachments/assets/d2cc8e4b-885b-4d04-aa5e-0ed07f49a507)


Profit: 
- The total profit for the three years is $4.5M.
- Previous profit was $4.42M, with a profit variance of $103.97K.
![profit](https://github.com/user-attachments/assets/f24e3387-4ee8-4695-82f4-b2f6ead05937)

Sales vs. Profit by Top 5 Products: 
- Chocolate Truffle has the highest sales of $ 3,731,000 and the highest profit of $1,537,934.
- Nougat follows with total sales of $2,056,546 and a profit of $400,221, and so on.
![sales  vs profit by top 5](https://github.com/user-attachments/assets/b0b34a86-bd05-4913-bd9e-0bbeb10470f3)

Total Orders by Region: 
- The South Region has the highest orders at 30.09%, followed by the West Region at 28.67%, and the Midwest Region at 26.53%.

Sales for Selected Year vs. Previous Year: 
- The highest sales occurred in December with $2,359.37K, followed by November with sales of $2,348.05K.

![sales selected year vs privous year (1)](https://github.com/user-attachments/assets/2e5cb774-c75b-464b-9f54-58596b8a912a)

Total Sales and Profit by State: 
- The state with the highest sales is California with a sales value of $1,059,586, followed by Indiana with $864,963, and Oregon with $714,818.

The top 5 customers based on their sales are: 
- E. Ltd: $429.00K
- Pure Group: $428.70K
- S.S.S Group: $422.13K
- Wuxi Group: $417.38K
- Capweld: $414.95K

The top 5 customers that contributed the highest profit are: 
- Wuxi Group: $116.81K
- Exact-Rx: $112.54K
- Pure Group: $109.35K
- OUR Ltd: $104.34K
- 3LAB: $103.95K
![top 5 customer by profit](https://github.com/user-attachments/assets/c0313659-9bc8-4c72-a391-2cc7de3e2d5e)

Total Orders by Warehouse Code: 
- The warehouse with the highest orders is AXW291 with 6K (47.2%), followed by GUT930 with 3K (23.08%), and NXH382 with 3K (19.96%).
- The warehouse with the least orders is FLR025 with 1K (9.76%).

Recommendations: 
1. Focus on High-Performing Products:
- Chocolate Truffle and Nougat are driving significant sales and profit. Consider expanding the range of these products or offering promotions around them to boost further sales.
- Conduct market research to understand why these products perform well and apply those strategies to lower-performing products.

2. Target Regional Growth:
- The South and West regions are leading in orders, indicating strong customer bases. Consider tailoring regional marketing campaigns, promotions, or launching limited-edition products specifically for these regions.

3. Increase Efficiency in Warehouses:
- AXW291 leads in orders, but the efficiency of smaller warehouses like FLR025 (with the lowest orders) should be examined. Optimizing inventory management or logistics in underperforming warehouses could reduce costs and improve order fulfillment.