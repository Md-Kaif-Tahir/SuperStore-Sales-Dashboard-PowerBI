![banner](Assets/Banner.jpg)

# SuperStore Sales PowerBI Dashboard 🚀
***"Unlocking Sales Insights: Your Dynamic Business Navigator"***

## Author
- [@Saad Haroon](https://github.com/saadharoon27) 📊🔍

## Table of Contents
- [Project Objectives](#project-objectives) 🎯
- [Data Source](#data-source) 📂🔍
- [Column Overview](#column-overview) 📊
- [Quick Glance At The Dashboard](#quick-glance-at-the-dashboard) 👀🚀
- [Method](#method) 📈
- [Selection Of KPIs](#selection-of-kpis) 🎯
- [Selection of Charts and Visualisation Options](#selection-of-charts-and-visualisation-options) 📊🎨
- [Steps in Data Cleaning](#steps-in-data-cleaning) 🛠️🧹
- [Data Filters (Slicer)](#data-filters-slicer) 🗺️🔍
- [Sales Forecasting Dashboard](#sales-forecasting-dashboard) 📈🔮
- [Business Insights](#business-insights) 💡🚀

## Project Objectives
- 1. **Spot Profitable Categories and Sub-Categories:**
   - Uncover the driving forces behind *revenue* and *profits* within product categories and sub-categories.
   - Craft strategies to amplify success in these key segments.

- 2. **Revamp Shipping Methods:**
   - Assess the effectiveness of different *shipping methods* in terms of *revenue generation*.
   - Recommend enhancements or alterations to the existing *shipping strategies*.

- 3. **Dive into Year-on-Year Analysis:**
   - Delve into *year-on-year sales* and *profit trends* to decipher *growth patterns*.
   - Identify pivotal factors influencing changes in *revenue* and *profit*.

- 4. **Geographical Insights Unveiled:**
   - Unearth insights into *sales performance* across different *states*.
   - Identify *high-revenue states* and untapped *growth areas*.

- 5. **Craft Customer Segment Strategies:**
   - Grasp the role of different *customer segments* in *sales*.
   - Develop targeted strategies catering to the most *profitable segments*.

- 6. **Payment Method Optimization Odyssey:**
   - Decipher the *popularity of payment methods* among customers.
   - Propose incentives or enhancements to foster the use of *preferred payment methods*.

## Data Source
- [SuperStore Dataset](https://www.kaggle.com/datasets/saadharoon27/superstore-dataset) 📂🔍

## Column Overview

| **Column Name**  | **Description**                                              |
|------------------|--------------------------------------------------------------|
| **Row ID**       | Identifier for each data row.                                |
| **Order ID**     | Unique order identifier.                                     |
| **Order Date**   | Date of order placement.                                     |
| **Ship Date**    | Date of order shipment.                                      |
| **Ship Mode**    | Mode of shipping for the order.                               |
| **Customer ID**  | Unique customer identifier.                                   |
| **Customer Name**| Customer's name.                                              |
| **Segment**      | Customer segment classification.                              |
| **Country**      | Country where the order was placed.                           |
| **City**         | City where the order was placed.                              |
| **State**        | State where the order was placed.                             |
| **Region**       | Region where the order was placed.                            |
| **Product ID**   | Unique product identifier.                                    |
| **Category**     | Broad category of the product.                                 |
| **Sub-Category** | Specific sub-category within the product category.             |
| **Product Name** | Name of the product.                                          |
| **Sales**        | Total sales amount for the order.                              |
| **Quantity**     | Quantity of the product ordered.                              |
| **Profit**       | Profit earned from the order.                                 |
| **Returns**      | Information about returns (0 for no return, 1 for returned).  |
| **Payment Mode** | Mode of payment used for the order.                            |
| **ind1**         | (Empty column)                                                |
| **ind2**         | (Empty column)                                                |

## Quick Glance At The Dashboard
**In a Glimpse**
![dashboard](Assets/Glance1.png)
------------------------------------
**Forecasting Fortune**
![forecasting](Assets/Glance2.png)

## Method
- Delving into the data with a keen eye for patterns and insights. 📊📈

## Selection Of KPIs
- **Sales:** The sum of all transactions, offering an overview of the *revenue*.
- **Profit:** Merging *revenue* and *costs* to unveil the net *profit*.
- **Quantity:** Aggregating *units* or *items* sold, illuminating *customer demand*.
- **Avg Shipping Days:** Calculating the average days for orders to reach *shipping*.

## Selection of Charts and Visualisation Options
- 1. **Sales By Category – Clustered Bar Chart:** Utilized a *stacked column chart* for "Sales By Category." Reveals the revenue contribution of each category, aiding in understanding category-wise performance.

- 2. **Top 5 Sub Categories – Clustered Bar Chart:** Transformed the chart to showcase the *top 5 sub-categories* contributing the most *revenue*. Delving deeper into profitable product segments.

- 3. **Sales By Ship Mode – Clustered Bar Chart:** Illuminates the *revenue* generated by distinct *shipping methods*, discerning their effectiveness and impact on the bottom line.

- 4. **Monthly Sales YoY – Area Chart:** Captures the *year-on-year sales trends*, showcasing the substantial growth in *revenue* during 2020.

- 5. **Monthly Profit YoY – Area Chart:** A companion in the exploration of *profit trends*, unveiling patterns mirroring the sales trajectory.

- 6. **Sales by State – Map Chart:** Unveiling the geographical impact on *sales* and *profit*, empowering strategic decisions based on regional insights.

- 7. **Sales by Customer Segment – Donut Chart:** Offering a visual treat of the contribution of each *customer segment* to the total *sales*, spotlighting the dominance of the *Consumer Segment*.

- 8. **Sales by Payment Mode – Donut Chart:** An artistic representation of *payment method preferences*, highlighting the dominance of *cash on delivery*.

## Steps in Data Cleaning
1. **Column Removal:** Bid farewell to two empty columns, '**ind1**' and '**ind2**,' streamlining the dataset for focused analysis.

2. **Returns Column Modification:** All instances of '**#N/A**' in the '**Returns**

' column transformed into '0,' simplifying data representation.

3. **AvgDelivery Column Addition:** Welcomed a new column, '**AvgDelivery**,' calculating the shipping duration in days for each order.

4. **SalesForecast Table Creation:** Forecasting dreams came true with a new table, '**SalesForecast**,' providing a daily order trend overview.

## Data Filters (Slicer)
- **Region Slicer:** Enabling a granular view, this slicer focuses on *Central*, *East*, *South*, and *West* regions, unlocking detailed regional patterns.

## Sales Forecasting Dashboard
- **Forecasting Canvas:** A new territory, '**Forecasting**,' showcasing future sales patterns with a 15-day forecast and a 95% confidence interval.

## Business Insights
1. **October's Enigma:** Unraveling the mystery of higher profits in October amid a sales dip, prompting curiosity around unique strategies or campaigns during this period.

2. **Standard Shipping Sweet Spot:** The majority preferring *standard delivery*, possibly indicating a highly price-sensitive customer base. A chance to optimize costs and maintain customer satisfaction.

3. **Cash on Delivery Craze:** The love for *cash on delivery* highlighted. Exploring opportunities to boost *credit card usage* through incentives and promotions.

4. **Customer Segment Power Play:** The *Consumer Segment* reigning supreme with a *48.09%* contribution to total *sales*. Crafting personalized strategies for key segments.

5. **Payment Method Palette:** A diverse canvas with various *payment methods*. A journey to encourage diversified usage for enhanced profitability. 💳🌐
