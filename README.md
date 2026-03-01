# Car-Sales-Analysis-on-Ms-Excel
---

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Objective](#objective)
- [Methodology](#methodology)
- [Tools Used](#tools-used)
- [Analysis Summary](#analysis-summary)
- [Key Findings ](#key-findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

--

## Project Overview
This project analyzes a car sales dataset using Microsoft Excel to extract business Insights related to revenue generation, pricing, sales performance and profitability. The analysis focuses on understanding sales trends, identifying high-value cars,evaluating electric vehichle performance, and assessing salesperson effectiveness.

---

## Problem Statement
The car sales company generates large volumes of sales data but does not have clear visibility into which car models generate the most revenue, how electric cars perform compared to other vehicles, and which salespersons contribute most to overall performance.

---

## Objective 
1.	Calculate the total revenue generated from car sales
2.	Identify the car with the highest sale price
3.	Determine the average sale price of electric cars
4.	Classify sales transactions based on performance levels
5.	Evaluate salesperson performance using sales counts
6.	Identify profitable electric car sales

---

## Methodology
The analysis followed a structured, step-by-step approach:
1.	Data Understanding
Reviewed the dataset to understand variables such as car type, sale price,
salesperson, and profit.
2.	Data Preparation
ensured data consistency, removed blanks, and organized columns for analysis.
3.	Exploratory Analysis
Applied Excel formulas to calculate totals, averages, and maximum values.
4.	Classification Logic
Used logical conditions (IF statements) to classify sales and salesperson
performance based on defined thresholds.
5.	Profitability Analysis
Filtered electric car sales and analyzed profit values to identify profitable
transactions.
6.	Insight Generation
Interpreted results to highlight revenue trends, performance patterns, and
business-relevant insights.

---

## Tools Used
•	Microsoft Excel
•	Excel Functions:
o	SUM
o	MAX
o	AVERAGE
o	COUNTIF
o	IF
•	Data filtering and sorting
•	Basic Excel tables and formatting

---

## Business Questions Answered
 1. Total Revenue from Sales
 2. Identifying the Car with the Highest Sale Price
 3. Average Price of Electric Cars
 4. Sales Performance Classification
 5. Salesperson Performance Classification
 6. Identifying Profitable Electric Car Sales

---

## Analysis Summary
### Total Revenue from Sales
  * Objective: Calculate the total revenue generated from all car sales. 
  * Approach:The SUM function was applied to the sales price column to compute total revenue.
    
### Identifying the Car with the Highest Sale Price
   * Objective:Determine the car model with the highest recorded sale price.
   * Approach:The MAX function was used to identify the highest sale value, and the corresponding car model was retrieved.

### Average Price of Electric Cars
   * Objective:Calculate the average sale price of electric vehicles.
   * Approach:Data was filtered to include only electric cars, and the AVERAGE function was applied.
     
### Sales Performance Classification
   * Objective: Classify sales transactions based on performance level.
   * Classification Logic:
      - High Performance → Sales ≥ 100,000
      - Medium Performance → Sales between 50,000 and 99,999
      - Low Performance → Sales < 50,000
   * Approach:The IF function was used to assign performance categories.

### Salesperson Performance Classification
   * Objective:Evaluate salesperson performance based on the number of cars sold.
   * Approach: A list of salespersons was created using the salesperson names in the dataset.The COUNTIF function was used to calculate the number of cars sold by each salesperson.An IF statement was then applied to classify salesperson performance based on predefined thresholds.
   * Formulas Used: =COUNTIF(Salesperson_Range, Salesperson_Name)
                     =IF(Sales_Count>=10,"High Performer",IF(Sales_Count>=5,"Average Performer","Low Performer"))
   
### Identifying Profitable Electric Car Sales
   * Objective:Identify electric car sales that generated positive profit.
   * Approach:Electric car transactions were filtered, and profit values were analyzed to identify profitable sales.

---

## Key Insights
•	Electric vehicles are commanding a price premium, consistently outperforming non-electric models in average transaction value.

•	Salesperson performance varies significantly, with clear distinctions between top performers, average performers, and those needing improvement.

•	Total revenue analysis shows the overall financial performance of car sales and highlights the company’s sales capacity.

•	Performance and profit flagging streamlines the decision-making process, allowing management to identify emerging trends and act on them in real-time.

•	While electric cars generally sell at higher prices, not all electric car sales are profitable, indicating the need for better cost control strategies.

---

## Recommendations
1.	Provide tailored professional development for underperformers, focusing on gaps in skills, product knowledge, or customer engagement.
2.	Flagging trends improves decision-making, Implement automated alerts for declining sales, unprofitable products, or inventory bottlenecks. Prioritize effort on clients contributing most to profit.
3.	Not all high-ticket items (like electric cars) are profitable. Adjust pricing to ensure profitability without sacrificing competitiveness. Focus marketing efforts on the most profitable Electric car models.
4.	Maximize long-term profitability by offering exclusive inventory and bespoke services to high-net-worth clients to drive recurring, top-tier revenue.

---

## Conclusion
This analysis demonstrates how Microsoft Excel can be effectively used to perform data analysis, classification, and business decision-making using structured datasets.



  







