# Car-Sales-Analysis-on-Ms-Excel
---

## Project Overview
This project analyzes a car sales dataset using Microsoft Excel to extract business Insights related to revenue generation, pricing, sales performance and profitability. The analysis focuses on understanding sales trends, identifying hihg-value cars,evaluating electric vehichle performance, and assessing salesperson effectiveness.

---

## Business Problem
The car sales company generates large volumes of sales data but does not have clear visibility into which car models generate the most revenue, how electric cars perform compared to other vehicles, and which salespersons contribute most to overall performance.

---

## Business Questions Answered
 1. Total Revenue from Sales
 2. Identifying the Car with the Highest Sale Price
 3. Average Price of Electric Cars
 4. Sales Performance Classification
 5. Salesperson Performance Classification
 6. Identifying Profitable Electric Car Sales

---

## Tools Used
- Microsoft Excel
- Excel functions (Sum, Max, AverageIf, If, Index, Average)

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
   Salesperson Performance Classification
**Objective:**  
Evaluate salesperson performance based on the number of cars sold.
**Approach:**  
A list of salespersons was created using the salesperson names in the dataset.The COUNTIF function was used to calculate the number of cars sold by each salesperson.
An IF statement was then applied to classify salesperson performance based on predefined thresholds.
**Formulas Used:**
=COUNTIF(Salesperson_Range, Salesperson_Name)
=IF(Sales_Count>=10,"High Performer",
   IF(Sales_Count>=5,"Average Performer","Low Performer"))
   
### Identifying Profitable Electric Car Sales
   * Objective:Identify electric car sales that generated positive profit.
   * Approach:Electric car transactions were filtered, and profit values were analyzed to identify profitable sales.

---

## Key Insights
•	Electric vehicles are commanding a price premium, consistently outperforming non-electric models in average transaction value."
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



  







