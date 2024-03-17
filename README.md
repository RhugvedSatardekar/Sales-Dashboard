# Sales-Dashboard

## Dashboard Link : https://app.powerbi.com/reportEmbed?reportId=0aa2efaa-c626-40fb-8281-2217bef8e40d&autoAuth=true&ctid=6b2b9958-0b17-48e1-b985-40c7199284ef

#### Welcome to My Power BI Sales Dashboard Project

## Project Overview

In this project, I aim to provide comprehensive insights into sales, profit, orders, profit margin, and various comparisons using Power BI. The primary objective of this sales dashboard is to analyze key performance indicators and trends, enabling stakeholders to make data-driven decisions effectively.

## Project Objectives

- Calculate Total Sales
My dashboard calculates and displays the total sales value for the selected period, offering a clear view of the overall revenue generated.

- Calculate Profit
I also visualize the total profit achieved based on the sales data, providing valuable insights into the financial performance of the business.

- Analyze Orders
By analyzing the number of orders placed during the selected period, this dashboard helps identify sales patterns and order trends.

- Calculate Profit Margin
I calculate and visualize the profit margin percentage, allowing stakeholders to assess the profitability of products or services.

- Compare Sales by Product with Previous Year
The dashboard compares sales performance for each product between the selected period and the previous year, highlighting growth or decline in sales.

- Compare Sales by Months with Previous Year
I also compare sales performance across different months, enabling stakeholders to identify regions with significant changes and trends.

- Display Top 5 Cities
A visualization showcasing the top 5 cities based on sales is included, helping stakeholders quickly identify the most lucrative locations.

- Compare Profit by Channel with Previous Year
The dashboard compares profit generated by each channel between the selected period and the previous year, indicating improvements or challenges in profitability.

- Analyze Sales by Customer and Compare with Previous Year
I analyze sales data by customer, highlighting the performance of individual customers and comparing it to the previous year.

- Create Slicers for Date, City, Product, and Channel
To enhance user interaction, I provide slicers for selecting specific dates, cities, products, and channels. This allows for dynamic filtering and personalized analysis, empowering stakeholders to explore data based on their preferences.



### My End-to-End Power BI Project Journey

1️⃣ Gather Data:
I started my Power BI project by collecting relevant data from various sources, including databases, spreadsheets, and web services. Ensuring data accuracy and relevance was crucial to achieving my project objectives.

2️⃣ Power Query - Data Extract, Transform & Load:
Utilizing the Power Query Editor in Power BI, I performed data cleaning and transformation tasks. This involved actions like removing duplicates, handling missing values, and merging datasets to prepare the data for analysis.

3️⃣ Create a Date Table:
I created a date table using Data Analysis Expressions (DAX) to leverage time intelligence functions effectively. This step was essential for conducting time-based analysis in my project.

4️⃣ Develop Data Model in Power BI Desktop:
Designing and building a robust data model was the next step. I established relationships between different tables, defined keys, and set up hierarchies to ensure accurate analysis and visualization.

5️⃣ Develop Reports in Power BI Desktop:
Using Power BI Desktop, I crafted insightful reports with visualizations like charts, tables, and maps. I added interactive features such as filters and slicers to enhance user engagement and data exploration.

6️⃣ Implementing DAX Calculations:
Leveraging the power of Data Analysis Expressions (DAX), I created calculated columns, measures, and tables for complex calculations and aggregations. This allowed me to derive meaningful insights from the data.

for creating new column following DAX expression was written;
       
        //Measures Total Sales
        Sales = SUM(Sales_Data[Sales])

        //Measures Previous Year Toal Sales
        Sales PY = CALCULATE([Sales], SAMEPERIODLASTYEAR(DateTable[Date]))

        //Diffrence Between Current Year Sales & Previous Year Sales
        Sales vs PY = [Sales] - [Sales PY]

        //Percentage Increase or Decrease in sales year on year (YOY%)
        Sales vs py % = DIVIDE([Sales vs PY],[Sales],0)





        >> Products Sold = SUM(Sales_Data[Order Quantity])
        >> Profit = SUM(Sales_Data[Profit]) 
        >> Profit LY = CALCULATE([Profit], SAMEPERIODLASTYEAR(DateTable[Date]))
        >> Profit Vs LY = [Profit]- [Profit LY]
        >> Profit vs LY % = [Profit Vs LY]/[Profit]
        >> Profit Margin = DIVIDE([Profit],[Sales],0)
        >> Total Cost = SUM(Sales_Data[Total Cost]) 



✨ Conclusion of Power BI Sales Dashboard Project ✨

This Power BI Sales Dashboard project aims to empower stakeholders with actionable insights and facilitate informed decision-making. Feel free to explore the dashboard and interact with the data using the provided slicers for a personalized analysis experience.

### Based on my analysis:

Sales saw a decrease of over 10% compared to the previous year.
There was a noticeable drop in sales for the top 7 products.
Specific customers contributed to the decline in sales.
The Export channel showed a higher profit margin.
These insights and more were derived from the comprehensive Power BI Sales Dashboard project I successfully executed.




        
# Snapshot of Dashboard1 (Power BI Service)

![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/9c3b2a1d-918f-43f7-98cc-5000d650beb4)

# Snapshot of Dashboard2 (Power BI Service)

![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/43c072bd-4331-43a2-a236-8f5a6f401549)

# Snapshot of On-Hover custom report tooltip (Power BI Service)
![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/35697f70-2151-4f9b-a504-9f57d5df1a2c)

# Snapshot of Star Schema Data Model (Power BI Desktop)     
 ![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/f2e65570-a15d-403f-b959-cded87c23b01)


 ## - Some other insights
 
 ![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/d0ec4895-845d-4247-a1c2-8e8b505e1cf8)
 
 ## - Deployment Pipeline of Sales Dashboard Project before publishing app 
 ![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/6f8c57f3-346e-4e03-92b4-33599e592c18)



 ## - Publishing an app along with multiple content of workspace with underlying Dataset to entire organization
 ![image](https://github.com/RhugvedSatardekar/Sales-Dashboard/assets/163725285/70365fc3-2fa3-45f1-abbe-1c0a73b897bd)

