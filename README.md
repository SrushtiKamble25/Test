
# Cars Product Sales-Dashboard


## Problem Statement

Businesses dealing in automobile sales often struggle to analyze and optimize their sales performance due to the complexity of handling multiple products, locations, and timeframes. Understanding which products generate the highest revenue and profit, identifying trends in sales over time, and recognizing regional demand variations are crucial for strategic decision-making. This dashboard aims to provide a comprehensive visualization of product sales, profit margins, and order patterns to facilitate data-driven decision-making.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section.
- Step 3 : Also since by default, profile will be opened so you need to select.
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : For calculating profit, null values were not taken into account as only less than 1% values are null in this column.
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added.
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.


In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating profit for each of the parameters.
Here is the graph representation used in tooltip:

![Image](https://github.com/user-attachments/assets/321ee5ee-bd30-419a-aaf9-f3b0cc2f611c)


Another tooltip is:


        
Product Sales Data Analytics Dashboard

Overview

The Product Sales Data Analytics Dashboard provides a comprehensive overview of sales performance, profitability, and product demand trends over multiple years. This interactive dashboard is designed to help businesses analyze sales distribution across different product lines, track high-performing products, and monitor overall financial metrics.

Key Metrics and Insights

1. Financial Performance

Total Profit: $3.8M

Total Profit Margin: $9.6M

Sales Growth (2003 vs 2004): $0.43M (+54.97%)

2. Top Performing Products

The most ordered product is the 1992 Ferrari 360 Spider Red, with the highest sales volume.

Other high-revenue products include:

2001 Ferrari Enzo ($0.19M sales)

1952 Alpine Renault 1300 ($0.19M sales)

2003 Harley-Davidson Eagle Drag Bike ($0.17M sales)

1968 Ford Mustang ($0.16M sales)

3. Sales Analysis by Product Line

Classic Cars contribute the highest revenue (40.1%).

Other major product lines include:

Vintage Cars (18.7%)

Motorcycles (11.7%)

Trucks & Buses (10.7%)

Planes (9.9%)

Ships (6.9%)

4. Quantity Ordered Over Time

The highest order volume was in 2004 (48K orders), followed by 2003 (36K orders), with a significant drop in 2005 (16K orders).

Monthly sales analysis shows a peak in December, indicating strong year-end demand.

5. Geographical Sales Distribution

The dashboard provides an option to filter sales data by country, including Australia, Austria, Belgium, Canada, Denmark, and Finland.

6. Inventory Analysis

The 1992 Ferrari 360 Spider Red has the highest stock availability (8K units).

Other products with high stock include 1952 Alpine Renault 1300 (7K units) and 2003 Harley-Davidson Eagle Drag Bike (6K units).

Dashboard Features

![Image](https://github.com/user-attachments/assets/b50a5c2a-3e01-43c9-9113-04403be26120)

Interactive Visuals: Users can filter data by year, product line, and country.

Trend Analysis: Line charts show sales trends over time.

Profitability Insights: Bar charts highlight the most profitable products.

Order Tracking: Sales and order volume are analyzed per month, quarter, and year.

Page 2:
![Image](https://github.com/user-attachments/assets/23a49294-9f38-4438-91d3-f43d4803917b)

Page3:
![Image](https://github.com/user-attachments/assets/c00909a9-297c-4e1c-9f0e-f4288716ded3)

Conclusion

This Power BI dashboard serves as a powerful tool for sales performance analysis, helping businesses identify best-selling products, monitor inventory levels, and track revenue growth over multiple years. With interactive filters and visual insights, stakeholders can make data-driven decisions to optimize sales strategies.
