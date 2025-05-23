# Supply Chain Analysis and Report

## Table of Contents

* [Project Overview](#project-overview)
* [Data Sources](#data-sources)
* [Tools](#tools)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Results and Findings](#results-and-findings)
* [Overall Summary](#overall-summary)
* [Recommendations](#recommendations)

### Project Overview

This data analysis projects focuses on supply chain analystics. The aim is to help solve **Key Shipment and Inventory Management Challenge** of a Logistics and Supply firm called *Just In Time*. By analyzing various aspects of the Supply chain Datasets, We seek to analyze supply chain inefficiencies and create insightful dasboard to inform business stakeholders about potential problems and propose structural bbusiness improvements. 

### Data Sources

Supply Chain Dataset: The primary dataset used for this analysis is the "Supply_Chain_Dataset.xlsx" file, which contains Four(4) Sheets;
  1. Data Dictionary: A dimension table with four(4) columns. A dictionary describing the column names used in the entire datasets.
  2. Fulfillment Sheet: A dimension Table with two(2) columns detailing product names and Warehouse Order Fulfillment in days.
  3. Inventory: A dimension Table with four(4) columns. It contains the product names, YearMonth, Warehouse Inventory and Inventory Cost per Unit columns.
  4. Orders_and_Shipments: A **Facts Table** Containing twenty(20) columns detailing Order information, Product information, Customer Information , Warehouse country, Shipment dates and time and lastly columns for Gross Sales, Discount(%) and Profit.

### Tools

* Power Query - Data Transformation and Cleaning.
* Power BI - Creating reports.

### Exploratory Data Analysis

EDA involved exploring the supply chain datasets to answer key questions, such as:
  * Analyze supply versus demand ratio.
  * Analyze key shipment and inventory management.
  * Overstock or understock.
  * Shipment delays.
  * Analyze YoY sales growth.
  * Propose structural business improvements.

### Results and Findings

![2015](https://github.com/user-attachments/assets/f973f2a2-f7e1-4aa5-b635-90358cbc596b)
![2016](https://github.com/user-attachments/assets/fca226c6-a8f1-4d01-a8f0-cd88e133ab69)
![2017](https://github.com/user-attachments/assets/8deb4307-5404-435f-9d02-3928455b4bbf)


#### Summary Report: 2015 - 2017

1. **Year-over-Year (YoY) Sales Growth**
	  * **2015:** Growth was positive, but exact % not shown.
	  * **2016:** Modest YoY increase of +4.62%.
	  * **2017:** Significant decline of −16.10%, indicating serious performance issues.

2. **Key Metrics Overview**

   |  Metric  |  Profit  | Inventory Turnover  | Net Sales  |
   |:---------|:---------|:--------------------|:-----------|
   |  2015    |  $1.3M	|	10.49	|	$2M	|
   |  2016    |  $1.4M	|	11.02	|	$2M	|
   |  2017    |  $1.1M	|	10.10	|	$2M	|

**Insight:** Net Sales remained flat across all years, while profit declined in 2017. Inventory turnover peaked in 2016 but dropped in 2017.

3. **Shipment Delay Trends**

   - **2015:** Shipment delays peaked in **January–March** with an improving trend through the year.
   - **2016:** Shipment delays started positive but dropped into negative delay territory by mid-year.
   - **2017:** Continued improvement with strong negative delay values, meaning shipments were early.

**Insight:** Logistics efficiency improved year-over-year, especially in 2017.

4. **Inventory Value by Month**

   -	**2015 & 2016:** Inventory peaks seen in **March–May**, suggesting seasonal stocking.
   -	**2017:** Sharp decline in inventory from **October to December**, indicating possible stock-outs or inventory optimization strategy.

5. **Inventory & Sales Quantity Trend**

   -	**All years:** Inventory levels were higher than sales quantity.
   -	**2017:** A steep drop in inventory and sales from **October** hints at operational or demand disruptions.

6. **Profitability by Product Category**

Top 3 product categories by % profit were consistent:
	-	**Cleats, Fishing, and Cardio Equipment, Women's Apparel** led across all years.
	-	**CDs, Toys, Men's Clothing, Books, Basketball and Baby** were the lowest performers.

7. **Customer Market Analysis**
   
	-	Supply consistently exceeded demand in all markets, especially in **Africa** and **Latin America(LATAM)**.
  	*	Stock Status:
		-	All markets were marked as **Overstocked** throughout the years.
   		-	**Balanced** status only occurred at the Total level due to aggregation.
	-	**Supply & Demand Ratios:** Extremely high in **Africa**, consistently signaling inefficiency.

8. **Discount Trends**

	-	Sum of Discounts rose from ~$1,078K (2015) to ~$1,140K (2016), but dropped to ~$907K (2017).
	-	Suggests a pullback in discounting efforts, possibly due to declining profitability.

### Overall Summary

![Overall](https://github.com/user-attachments/assets/73d5bfde-f821-4e65-bc82-0e83736f038a)


1.	**Performance Highlights:**

   	-	**YoY Sales Growth: +42.89%** – Strong growth
	-	**Total Profit: $3.8M** – High profitability
	-	**Inventory Turnover: 31.7** – Indicates healthy inventory flow
	-	**Net Sales: $5M** – Sales remain strong year-round

2.	**Risks Identified:**
   
   	*	Consistent overstock in **5 of 6 regions** — may lead to higher holding costs
	*	Seasonal shipment delays in **August–October** — supply chain bottlenecks?
	*	High discounts in LATAM & Europe – check for margin erosion

### Recommendations

1.	**Declining Profitability & YoY Sales in 2017** signals a need to reassess pricing, product mix, or customer strategy.
2.	**Shipment performance improved**, which is a positive indicator for operational logistics.
3.	**Chronic overstocking** in all regions implies misalignment in demand forecasting and procurement.
4.	Focus on **stock optimization** in all regions.
5.	**The end-of-year drop in inventory and sales (2017)** may be a red flag — investigate potential supply chain disruptions or demand collapses.
6.	**High Discounts in LATAM and Europe** - check for margin erosion.


     













