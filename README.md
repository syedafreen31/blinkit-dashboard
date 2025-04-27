Blinkit Dashboard 📊

**Overview**

**Welcome to the Blinkit Dashboard!**

A one-stop platform designed to give you a comprehensive view of your sales outlets. Dive into the world of data-driven decisions with easy-to-read metrics and insights that help you analyze your sales performance, product success, and outlet specifics like never before. 📊

Features & Metrics
1. Total Sales 💰
Formula:
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
Track the total sales across all outlets in a given period. This is your big picture indicator for business performance.

2. Average Sales per Outlet 🏪
Formula:
Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
Get a quick overview of how much each outlet is bringing in on average. Perfect for spotting high-performers and underperformers.

3. Number of Items Sold 📦
Formula:
No of Items = COUNTROWS('BlinkIT Grocery Data')
See how many items have been sold across all outlets. A great way to measure product popularity and overall sales volume.

4. Average Rating ⭐
Formula:
Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
See how customers feel about your products. This metric gives a clear snapshot of customer satisfaction at each outlet.

5. Fat Content 🧀
Take a deeper look into the fat content of the products sold at each outlet. Ideal for health-conscious consumers and keeping up with dietary trends.

6. Fat Content by Outlet 🏠
A detailed breakdown of fat content sold at each outlet. Track healthy trends and preferences per outlet—because health matters.

7. Total Sales by Item Type 📊
See which categories (e.g., groceries, beverages, etc.) are driving the most sales. A key metric to optimize inventory and understand your product mix.

8. Outlet Establishment 🏗️
Know the history of each outlet by viewing when it was established. This helps in analyzing outlet maturity and its influence on sales growth.

9. Outlet Size 📏
Discover the size of each outlet and how it relates to its sales performance. Does a larger space lead to more sales? Let’s find out.

10. Outlet Location 🌍
Map your outlets geographically to compare their performance across regions. Know where your strengths and opportunities lie.

11. Outlet Type 🏬
Categorize your outlets (e.g., retail, kiosk, drive-thru) to see how different formats perform. Drive-thru vs. retail? Let’s find out which one takes the crown.

**How Are These Insights Calculated?**

All the insights you see are powered by DAX (Data Analysis Expressions), the engine behind custom calculations in Power BI. The core measures that fuel the Blinkit Dashboard are:

Total Sales:
SUM('BlinkIT Grocery Data'[Sales])

Average Sales:
AVERAGE('BlinkIT Grocery Data'[Sales])

Number of Items Sold:
COUNTROWS('BlinkIT Grocery Data')

Average Rating:
AVERAGE('BlinkIT Grocery Data'[Rating])

These DAX formulas give you an accurate, real-time view of your business performance at your fingertips. 🔍



