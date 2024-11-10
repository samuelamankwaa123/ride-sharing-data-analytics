# ride-sharing-data-analytics
SQL Data Analysis for Ride-Sharing Platform
Project Overview
This SQL script performs data analysis on a fictional ride-sharing platform dataset (c_trips_data). The analysis includes metrics on customer retention, driver performance, trip statistics, revenue per trip, and peak hours, among others. These metrics are designed to provide insights similar to those that might be valuable for ride-sharing platforms.

Dataset Structure
The dataset c_trips_data has the following columns:

TripID: Unique identifier for each trip
TripDate: Date (and possibly time) of the trip
CustomerID: Unique identifier for the customer
DriverID: Unique identifier for the driver
City: City where the trip occurred
StartLocation: Starting location of the trip
EndLocation: Ending location of the trip
Distance: Distance covered in the trip (in kilometers)
Duration: Duration of the trip (in minutes)
Fare: Fare charged for the trip
Status: Status of the trip (e.g., Completed, Canceled)
Rating: Customer rating for the trip
SQL Analysis Summary
1. Rename Columns
This script starts by renaming generic column names (c1, c2, etc.) to meaningful names for easier readability.

2. Total Trips, Total Revenue, and Average Revenue per Trip by City (Last Month)
Calculates the total number of trips, total revenue, and average revenue per trip by city for the past month.

3. Customer Retention Rate
Calculates the retention rate, defined as the percentage of customers who took a second trip within 30 days of their first trip.

4. Driver Performance
Identifies the top 5 drivers by average rating, excluding drivers with missing ratings.

5. Busiest Hour Analysis
Finds the hour of the day with the highest number of trips, giving insights into peak operating hours.

6. Monthly Revenue and Trip Analysis by City
Calculates total trips, total revenue, and average revenue per trip by city, aggregated by month.

7. Customer Segmentation
Segments customers based on their trip counts into "High", "Medium", or "Low" engagement levels.

8. Potential Churned Customers
Identifies customers who have not taken a trip in the last 30 days as potential churn risks.

9. Revenue Per Kilometer by City
Calculates the average revenue generated per kilometer for each city.

10. Most Popular Routes
Lists the 6 most popular routes based on trip count and provides the average duration for each route.

11. Driver Income Analysis (Last 2 Months)
Calculates total income for each driver over the past two months.

12. Trip Cancellation Rate by City
Calculates the trip cancellation rate as a percentage for each city.

How to Use
Run the SQL Script: Copy the SQL commands into an SQL-compatible environment (e.g., SQLite, MySQL) and execute them.
Data Insights: Analyze the output of each query to understand various aspects of the ride-sharing data, including customer behavior, driver performance, and operational metrics.
