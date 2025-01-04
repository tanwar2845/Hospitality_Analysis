Power BI dashboard - https://app.powerbi.com/view?r=eyJrIjoiOTMxYmQwZWMtZGM3MC00NTQ3LTg4YTItMDg0OGFhNjc1NWE0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

https://github.com/tanwar2845/Hotel-Grand/blob/main/Images/Screenshot.png
![problem](https://github.com/tanwar2845/Hotel-Grand/blob/main/Images/Screenshot.png)

# Atliq Grand Hotel Analysis
## SITUATION
Atliq Grand Hotel, a prominent player in the hospitality industry for over 20 years, has recently faced a decline in market share.
This downturn is attributed to strategic moves by competitors that disrupted Atliq Grand's stronghold. As a result, the hotel's 
revenue has significantly decreased, necessitating a comprehensive data-driven strategy to regain its competitive edge.

## TASK
Evaluating financial performance metrics like revenue, RevPAR (Revenue Per Available Room), and ADR (Average Daily Rate).
Assessing occupancy trends and customer behavior to identify operational inefficiencies.
Enhancing insights into customer satisfaction and booking patterns to improve service offerings.
Comparing Week-over-Week (WoW) performance metrics to identify trends and anomalies.

## ACTION
### Combined multiple datasets:
Revenue data-
fact_aggregated_bookings, 
fact_bookings for booking 

Dimension tables- 
dim_date, 
dim_rooms, 
dim_hotels 
for contextual information.
Established a star schema to optimize data relationships and enable advanced analytics.

Measure Development:
Created key performance measures, including:
Revenue, RevPAR, and ADR to monitor financial health.
Occupancy %, Realization %, and WoW metrics to track operational efficiency.
Ratings and Feedback Analysis to understand customer satisfaction.

Dashboard Design:
Built a multi-page dashboard to address specific focus areas:
Revenue & Occupancy View: Highlighted financial metrics and occupancy rates.
Booking Performance View: Focused on trends in bookings, cancellations, and platform distribution.
Customer Experience View: Provided insights into ratings, preferences, and customer feedback.

Insights & Visualization:
Incorporated advanced visuals like scatter plots, heat maps, and KPIs to reveal correlations and patterns.
Enabled dynamic filtering by dimensions such as city, room class, booking platform, and week number.

## RESULT

City-Specific Insights:
Hyderabad: Provides the second-highest number of bookings but has the lowest ADR.
Mumbai: Generates the highest ADR and contributes the most revenue.

Customer Satisfaction:
Atliq Seasons: Receives a poor average rating of 2.4, requiring immediate attention.
Bangalore: Despite having the highest average rating for Atliq Grand, the city's overall average rating is not very good.
Room Classes: Presidential rooms receive the highest overall average rating among all room classes.

Platform Performance:
MakeYourTrip: Emerges as the top platform, contributing the highest number of bookings.
