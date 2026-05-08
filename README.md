# Revenue Insights Dashboard

### Atliq-Hospitality Analysis

### 2.Purpose
AtliQ is a company that owns multiple hotel chains across various cities of India
The Managing director / CEO of AtliQ wants to incorporate ‘Business and Data Intelligence’ to identify and track the source of revenue for AtliQ hotels
Hence, it is decided to develop a KPI Dashboard for AtliQ, using May-22 to July-22 data, which can help track its revenue sources and other relevant KPIs across various dimensions
It’ll help the management take strategic business decisions based on the insights generated from the dashboard.


### 3.	Tech Stack
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

### 4.	Data Source
Source: Sourced From CodeBasics

### 5.	Features / Highlights
•	Business Problem
Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.

•	Walkthrough of Key Visuals<br>
A few measures were created to measure the KPIs as shown below:<br>
  Revenue = Sum of revenue_realized from Bookings table (in Rs.)<br>
	Total bookings = Count of booking_id from Bookings table<br>
	Avg rating = Average of ratings from Bookings table<br>
	Total capacity = Sum of capacity from Aggregated bookings table<br>
	Total successful bookings = Sum of successful bookings from Aggregated bookings table<br>
	Occupancy rate = Total successful bookings / Total capacity (in %)<br>
	Total cancelled bookings = Count of booking_id with status=‘cancelled’ from Bookings table<br>
	Cancellation rate = Total cancelled bookings / Total bookings (in %)<br>
	Avg stay duration = Average days stayed by customer in a room per booking<br>


•	Business Impact & Insights<br>
Mumbai generates highest revenue and Delhi the least revenue during May to Jul 2022<br>
Company need to focus on increasing the revenue in Delhi.<br>
The occupancy rate is higher during weekends across all cities, months and booking platforms.<br> Leverage this insight to increase revenue generated during weekends.<br>
70% of the bookings are checked out while 5% of booking don’t show up across all cities and booking platforms which means 75% of bookings generate revenue for AtliQ hotels. Identify and analyze the reasons for cancellations and try to reduce them.<br>
Avg rating varies between 3.4 to 3.8 across cities and avg stay duration is 2.4 for each booking. Compare it with the industry benchmark across cities and evaluate the performance.<br>
Occupancy rate is highest at Delhi with 60+ % for all months though generates least revenue compared to other cities. Identify the reason for higher occupancy and use that to drive the revenue growth.<br>


### 6.	Screenshots / Demos<br>
Show what the dashboard looks like.<br>
Example: ![Dashboard Preview](https://github.com/the-mansi-goel/Ski-dashboard/blob/main/Snapshot%20of%20the%20Dahbaord.png)
