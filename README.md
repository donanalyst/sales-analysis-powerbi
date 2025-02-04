# Super-Store Analaysis Report
**Sales performance from 2015 - 2018**

# Introduction & Background

The goal of this Super-Store sales analysis project is to understand the sales trends from 2015 to 2018. Below are some of the business questions that this dashboard can answer, helping business executives and end-users at Super-Store make better sense of their data. This project also serves as a demonstration of my skills and abilities in the field of Data Science.

# Business Objectives

List down below are the possible business questions:

- What are the overall sales trends? Are sales increasing or decreasing?

- How do current sales compare to the previous year?  

- What are the total sales by category and sub-category?  

- Which products are the top sellers?  

- Which products are underperforming?  

- How do sales vary by region? 

- Who are the top customers?

- How many orders are placed by each customer?

- Are there any seasonal patterns in sales?  

- What are the peak sales months?  

- What are the slowest sales months?

- Are sales meeting the yearly target?  

- What is the gap between current sales and the target?


# Data Source & Methodology

**Data Source:** The data for this analysis project was sourced from the popular site "kaggle.com."

**Data Cleaning:** Since the dataset is already clean, no further cleaning was necessary. However, I ensured that all data types were in the correct format and that there were no empty values, to avoid potential issues during analysis.

**Data Model:** The dataset uses a flat file schema, which simplifies analysis as there is no need for additional dimensional references. However, this data model may not be ideal for hourly sales analysis, as the large volume of data could slow down report generation or dashboard performance.

**Analysis Approah:** I utilized Power Query for data profiling to investigate potential issues. Additionally, I created a time dimension table for time intelligence analysis using DAX. I also used DAX to create key measures for analysis and visualization.


# Dashboard Features & KPI's

**Metrics:** The key metrics included in the dashboard are:

- Total Sales
- Total Orders
- Top Seller in each category, sub-category, and customer
- Year-over-Year (YoY) Growth in Sales

**Visualizations:**

- Line graphs to show the distribution of sales by month.
- Two tables to display sales across different customers and the number of sales by category and sub-category.
- A heat map to show the intensity of sales in different regions.


# Conclusion and Recommendation

**Summary:**

- Super-Store saw significant sales growth in 2018, surpassing the sales figures from 2017 and hitting the yearly target.
- The technology category maintained consistent sales performance, while the sub-category sales fluctuated between 'Phones' and 'Chairs.'
- From 2015 to 2018, the West Region recorded the highest sales, with $710K in total sales and 3,140 total orders. The East Region followed closely with $661K in sales and 2,774 orders. These two regions contributed greatly to the overall sales performance.
- A pie chart titled "Sales by Segment" shows that the Consumer segment contributed the most, with 50.91% ($1.1 million), which is nearly half of the total sales of Super-Store ($2.25 million).

**Recommendations:**

- The line graph showing the distribution of sales by month indicates significant declines in February, April, and June. These months consistently show lower sales across the years and should be further examined for potential anomalies or underlying causes.
- Several sub-categories also experienced significant sales declines in 2018, including Envelopes (-24.24%), Fasteners (-9.64%), and Machines (-22.11%). These declines should be investigated further, considering factors like product stock, customer feedback, and seasonal trends.


# Dashboard

![image](https://github.com/user-attachments/assets/469f0ed0-b7c5-483a-8028-40ccb0034a68)

