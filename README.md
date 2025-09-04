# Digital-Marketing-campaign-Performance-using-Power-BI-
Building an Interactive dashboard in Power BI
# Project Objective
The aim of this Project is to build a fully interactive dashboard to monitor campaign performance and help optimize future strategies. 

# Aim
I plan to achieve this by cleaning a clean, professional dashboard that clearly communicates key insights and allows for dynamic filtering across campaigns, dates, products, and marketing channels.

# Key Tasks
1.	Create Key Performance Indicators (KPI) for Total Ad Spend, Total Impressions, Total Clicks, Total Conversions, Total Revenue, and Overall RoI( Return on Investment).
2.	Create charts for Ad Spend by Channel, Clicks vs Impressions, Conversion Rate by Category, Revenue by Product, RoI by Product/Category. 
4.	Create time based trends for Spend, Conversions, ROI, and Clicks.
5.	Add slicers for Campaign Date, Product Name, Product Category, and Marketing Channel.
6.	Create calculated fields for CTR( Click Through Rate), Conversion Rate, and ROI Using DAX measures.

# Contents
 Step 1: Loading and transforming data in Power BI
 
 Step 2: DAX formulas and measures
 
 Step 3: Report
 
 Step 4: Dashboard
 
 Step 5: Future strategies, Recommendation/Suggestion.

# Step 1 (LOADING AND TRANSFORMING DATA IN POWER BI)
•	Download embedded data set through link 

•	Load data to Power BI clicking on Get data >> Excel workbook from the home tab 

•	Select dataset to open from the file manager icon that opens up.

•	Preview data by selecting the marketing table icon on the navigator pane and click load. 

•	Proceed to Transform the data using power query to clean any inconsistencies and dirty data.

•	After cleaning, which in this case was a clean data, close and apply.

# Step 2 (DAX MEASURES AND FORMULAS)
•	Navigate and select table view to view table 

•	In the dialogue box, proceed to type in the formulas needed to calculate CTR, Conversion Rate, Total Ad Spend, Impressions, Clicks, Conversions, Revenue, and Overall ROI  Using Measures.
 o	Click_Through_Rate = DIVIDE([Total_clicks], [Total_Impressions], 0)  
 
 o	Conversion_Rate = DIVIDE([Total_Conversions], [Total_clicks], 0)
 
 o	Overall_ROI = DIVIDE([Total_Revenue] - [Total_Ad_Spend], [Total_Ad_Spend],0)
 
 o	Total_Ad_Spend = SUM(marketing[Ad Spend (INR)])
 
 o	Total_clicks = SUM(marketing[Clicks])
 
 o	Total_Conversions = SUM(marketing[Conversions])
 
 o	Total_Impressions = SUM(marketing[Impressions])
 
 o	Total_Revenue = SUM(marketing[Revenue (INR)])

# Step 3 (REPORT)
•	Hover around the report page and select card visuals in the visualization pane.

•	The selected visual would show on the blank canvas.

•	Proceed to select the visuals you would like to view in the data pane.

•	To Check for Key Performance Indicators (KPI) for Total Ad Spend, Total Impressions, Total Clicks, Total Conversions, Total Revenue, and Overall RoI( Return on Investment), I used the card visual to achieve this.

•	To create charts for Ad Spend by Channel, Clicks vs Impressions, Conversion Rate by Category, Revenue by Product, RoI by Product/Category, I explored the use of bars, columns, tables, indices, donut charts to achieve this.

•	 To create time based trends for Spend, Conversions, ROI, and Clicks, I proceeded to us line charts to represent visuals.

•	I proceeded to add slicers for Campaign Date, Product Name, Product Category, and Marketing Channel to enable filtering. 

# Step 4 (DASHBOARD)
•	On a new page and a blank Canvas, select shape to be used as tile and arrange, edit and fit in visuals.

•	Proceed to edit charts to fit into the size of the dashboard to enable a clean, neat and clear dashboard.

•	Afterwards, format visuals, add colors, increase fonts in the card visuals, using the visualization pane for proper formatting to get a clear, visually appealing dashboard.

# Step 5 (FUTURE STRATEGIES, RECOMMENDATIONS/ SUGGESTIONS)
•	Based on the data provided, the highest selling product in revenue is the wheat flour generating a revenue of 11 million +
I would suggest that the company should never run out the product and always restock to aid product retention and customer orders.
	
•	Highest generating marketing Channel is Google ads with a revenue of 74 million +
With this, It proves that majority of their uses Google and as such tend to Trust the advertisements on the site. I would suggest the company activates it SEO( Search Engine Optimization) To further increase visibility and reach more customers.

•	Household Items and essentials has the highest conversion rate with 11.25% and a total conversion at 308,000+
I would suggest that more focus should be on household product categories and the company can stock up with more varieties to drive more sales targeting impulse buyers.

•	January was the peak month with the highest revenue, highest clicks, highest conversions, as well as Ad spend.
It could be deduced that at the first week of the month of January, the company made a lot in terms of revenue and it could be as a result of the amount spent on Ads for that month being the highest amount , i.e increase in Ad spend = increase in revenue.


