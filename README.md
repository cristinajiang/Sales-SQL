## **Sales Performance and Product Line Profitability Analysis For an Automotive Company**

This is a mini side project I completed using a public dataset to explore key business questions and support decision-making with SQL. It includes a problem statement, analytics goals, key questions, SQL code, and a summary of insights and recommendations. Before starting the SQL analysis, I ensured that the database schema was properly defined, including the primary keys for each table and the foreign keys, as shown in the image below: 
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/9f46c7fd98920df7f7486e6e0dc961a6e9735a3e/images/Schema%20.png) 

**Problem Statement:**
The sales team needs visibility into various ways to drive revenue and profit. Therefore, I have developed a subset of analytics goals and questions to help optimize the sales strategy. 

**Analytics Goals**
* Identify high-revenue and high-margin product lines
* Identify regions with the highest and lowest total revenue
* Analyze revenue trends over time
* Evaluate potential operational inefficiencies (e.g., late shipments)
* Highlight sales performance by employees (sales reps) and customers
* Provide actionable recommendations based on the data

*To help achieve the analytics goals, I have developed the following specific questions to be answered through data analysis:*

**Key Questions**
1. What are the top three product lines generating the highest revenue and profit margins?
2. Which region generates the most revenue? Which region generates the least revenue?
3. Is there any revenue trend over time?
4. How often are orders delayed? 
5. Who are the top 5 customers by total payment? 
6. Which employees are responsible for the highest customer revenue?

   
**SQL Codes** 

**1. What are the top three product lines generating the highest revenue and profit margins?**
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/a3e05c8929f9b8c0ef7ceb82ecc1c1cd0e44ae50/images/SQL%20Top%203%20Product%20Line.png) 

*Insights: The results show that top product lines's revenue does not equal profit. Classic Cars, Vintage Cars, and Motorcycles are the top 3 product lines by revenue. However, their profit margin ranks in reverse order — Motorcycles yield the highest margin. It shows that high revenue products don’t always maximize profit. There's room to shift focus or pricing.*


**2. Which region generates the most revenue? Which region generates the least revenue?**

By Highest Revenue: 
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Highest%20revenue.png)

By Lowest Revenue: 

![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Least%20Revenue.png)

Since Hong Kong’s revenue is only $45,480.79—approximately the average price of one car—I assume there was only one customer from Hong Kong. Let’s confirm this using actual data:

![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Sales%20in%20HK.png) 

*Insights: The USA leads in total revenue. Hong Kong has the lowest revenue, with only one customer and one sales rep. Market potential in Hong Kong may be untapped due to lack of salesforce and outreach.*

**3. Is there any revenue trend over time?**

![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/df4977c1bd95173934243eefb0d8d62144a8b408/images/Quarter%20Trend.png) 

*Insights: Revenue shows an overall increase from Q1 to Q4 each year, peaking in Q4. Strong seasonal performance may align with holiday sales cycles or Q4 promotions.* 

**4.How often are orders delayed?**
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/86607e7330d63efe7de3fe5c6e91efae77dec6b3/images/order%20ship%20date.png)

*Insights: Only one order delay was found, lasting 56 days, therefore, fulfillment operations appear reliable overall, but rare delays need root cause analysis.*

**5. Who are the top 5 customers by total payment?**
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/f79b2285dd2dfcf5d78220ea1f654315472f78a4/images/Top%205%20customers.png)

*Insights: The automotive company can retrieve information about the top 5 customers.*

**6. Which employees are responsible for the highest customer revenue?**
   
![SQL Command and Results](https://github.com/cristinajiang/Sales-SQL/blob/e2d0b4c83de0fb66dce2650d053e8439423fdff2/images/Sales%20Rep%20Performance.png)

*Insights: The automotive company can retrieve the names and details of its top sales performers.*

## **Next-Step High Level Recommendations to Increase Revenue and Profitability** 
1. Optimize Profit Strategy
* Promote high-margin products like Motorcycles more aggressively
* Revisit pricing or sourcing strategy for lower-margin, high-volume lines (e.g., Classic Cars)

2. Consider Expanding into Underserved Markets to Capture Untapped Revenue
* Conduct market research in Hong Kong and evaluate its potential for business growth and expansion

3. Strengthen Customer and Sales Rep Development Strategy
* Introduce a VIP loyalty program for top customers to encourage retention, repeat purchases, and referrals
* Target acquisition of mid-tier customers to broaden the customer base and increase revenue stability
* Pair top-performing sales reps with lower-performing ones through mentorship or training sessions to share best practices
* Recognize and reward high-performing sales reps to maintain motivation and retain talent

4. Investigate Rare Delays 
* Analyze the root cause of the 56-day delayed order
* Review logistics, supplier timelines, and internal processing for any bottlenecks

5. Plan Around Seasonal Trends
* Use Q4 revenue peak to plan targeted campaigns or product launches
* Consider early inventory ramp-ups and cross-sell strategies during high-demand periods


