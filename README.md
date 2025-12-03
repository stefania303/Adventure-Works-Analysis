# Adventure Works - Analysis

## Project overview

The goal of this analysis is to understand how Adventure Works' products and customers perform across different countries. Using sales, orders, and returns data, we want to find out which products and customer groups bring the most revenue, where most orders come from, and how returns impact the profit. This helps the business decide where to focus sales, marketing, and pricing efforts.

The report is built in Power BI and includes four main dashboards:

Executive Dashboard – high-level view of revenue, profit, orders, and returns, with trends over time.

Geographic Orders Dashboard – shows which countries generate the most orders.

Product Detail Dashboard – deeper analysis of product performance vs targets, including profit simulations.

Customer Detail Dashboard – focuses on customer value, segments, and how the customer base changes over time.

All dashboards are interactive so users can filter by product, country, year, and other dimensions to explore the data in more detail.



### 1. Executive Dashboard

It is designed for stakeholders who need a quick snapshot of business health and performance trends.

![Image](https://github.com/user-attachments/assets/02210f19-1707-4fa6-9ab2-bfc78e772bda)

#### Main metrics & KPIs:

- Total Revenue

- Total Profit

- Number of Orders

- Return Rate

#### Key features:

- Top & bottom product types by orders and returns, helping identify bestsellers as well as problematic product categories.

- Monthly performance cards showing:

        Revenue vs. previous month
        Orders vs. previous month
        Returns vs. previous month

- Weekly revenue line chart to track short-term trends and seasonality.

- Bar chart of top 3 categories by orders to highlight the most popular product categories.

- Top 10 products table showing detailed information for the best-performing products (e.g., revenue, orders, returns).

The dashboard is fully interactive: selecting a product category or year filters the rest of the visuals so users can drill down into specific segments of the business.



### 2. Map

This dashboard uses a map visual to show the geographic distribution of orders by country. It helps identify where most of the company’s demand is coming from and highlights top markets.
![Image](https://github.com/user-attachments/assets/9d5e1526-ec74-4303-abfb-2a4f991dc901)

### Key points:

Each country on the map represents locations where products have been ordered.

The United States and Australia stand out as the top two countries by order volume, indicating they are the company’s strongest markets.


### 3. Product Detail 

#### Product Detail Dashboard

The Product Detail dashboard provides deeper insights at the individual product level. It is designed to analyze how a specific product is performing over time against defined targets.

Using a page-level product filter, users can select a product and see all visuals update to show metrics only for that product.

![Image](https://github.com/user-attachments/assets/6f1555b1-2545-4b87-b6ad-4ab0ab2f4796)



#### Key KPIs:

- Monthly Orders vs Target

- Monthly Revenue vs Target

- Monthly Profit vs Target

These KPIs help evaluate whether each product is meeting performance expectations.

#### Main visuals:

- Weekly Profit vs Adjusted Profit (line chart) -> Shows Total Profit and Adjusted Profit by week.

Adjusted Profit is calculated based on a price adjustment parameter.

- Dynamic Weekly Metrics (line chart)

A metric selector (slicer) lets the user choose which metric to display by week:

        Orders
        Revenue
        Profit
        Returns
        Return %


### 4. Customer Detail

The Customer Detail dashboard focuses on customer behavior and value, helping understand who the most important customers are and how the customer base evolves over time.

![Image](https://github.com/user-attachments/assets/afdb2c47-f281-4599-855d-51d09f304f60)

#### Key KPIs:

- Unique Customers – total number of distinct customers.

- Revenue per Customer – average revenue generated per customer.

- Top Customer – highlights the customer with the highest revenue and number of orders.

#### Main visuals:

a) Customer Segmentation (donut charts)

    Orders by Income Level – shows how order volume is distributed across different income segments.

    Orders by Occupation – highlights which occupations generate the most orders.

b) Top Customers Table

    A detailed table listing the top 100 customers, including key metrics such as revenue and number of orders.

c) Customer Growth & Value Over Time (line chart)

    Tracks total customers over time (by week).

    Plots revenue per customer over time (by week) on the same chart to show how customer value changes as the customer base grows.



## Conclusion

This project was an exploratory analysis designed to help me practice and test different Power BI features. I worked through the full process, from raw data to interactive dashboards.

During this project I:

- Imported data from multiple tables into Power BI

- Cleaned and shaped columns (removing errors, changing data types, creating useful fields)

- Built a star schema data model and managed relationships between tables

- Created hierarchies for easier drilling down in visuals

-  Wrote calculated columns and measures using DAX

- Designed multiple visuals: line charts, bar charts, donut charts, KPI cards, tables, and maps

- Added slicers, filters, and parameters to make the report interactive

- Set up report interactions and custom tooltips to give more context on hover

- Created a left navigation bar using bookmarks to switch between report pages

Overall, this analysis helped me understand both the business data and the Power BI workflow: data preparation, modeling, DAX, and building interactive dashboards.
