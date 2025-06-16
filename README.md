# Sales-SQL
Sales Performance and Product Line Profitability Analysis For an Automotive Company
(This is a side project I did using a public dataset to explore key business questions and decisions using SQL)

🧩 Problem Statement 
The sales team needs visibility into which product lines are most profitable and which sales representatives and customers contribute most to revenue. This will help with optimizing regional marketing, inventory planning, and sales strategy.

🎯 Analytics Goals
Identify high-revenue and high-margin product lines
Identify countries with highest and lowest total revenue
Evaluate potential operation inefficiency (e.g., late shipments)
Highlight sales performance by employee (sales rep) and customer


❓Key Questions
1. Which product lines generate the highest revenue and profit margins?
2. Which country has the most revenue? Which country hasthe least revenue?
3. Who are the top 5 customers by total payment? 
4. Which employees are responsible for the highest customer revenue?
5. How often are orders delayed? 
   
SQL Codes: 
1. Which product lines generate the highest revenue and profit margins?
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/a3e05c8929f9b8c0ef7ceb82ecc1c1cd0e44ae50/images/SQL%20Top%203%20Product%20Line.png)

3. Which region has the most revenue? Which region has the least revenue?
USA is the country with the highest revenue:

![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Highest%20revenue.png)

The automotive company has the least revenue in HK: 

![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Least%20Revenue.png)

Since HK's revenue is only $   , which is around the average price for one car. I assumed that there was only one customer from HK. Let's confirm it using actual data: 

![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Sales%20in%20HK.png) 

3. How often are orders delayed?
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/e2d0b4c83de0fb66dce2650d053e8439423fdff2/images/Sales%20Rep%20Performance.png)

   
5. Who are the top 5 customers by total payment?
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Top%205%20customers.png)


7. Which employees are responsible for the highest customer revenue?
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/e2d0b4c83de0fb66dce2650d053e8439423fdff2/images/Sales%20Rep%20Performance.png)



Upon deeper analysis, we discovered that The Hong Kong market has not been actively developed. With just one customer and only one sales representative, the country remains significantly underpenetrated.

📈 Recommendation
The automotive company could consider:
Expanding sales capacity by hiring more representatives
Running a targeted marketing campaign to generate local demand
Conducting market research to assess potential demand in Hong Kong before further investment

