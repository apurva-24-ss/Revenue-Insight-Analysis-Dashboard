AtliQ Grands Business Intelligence Dashboard – Power BI Project

Project Overview
This repository contains a Business Intelligence dashboard built in Power BI for AtliQ Grands — a luxury and business hotel chain operating across India. Facing declining market share and revenue, the company made a strategic pivot to leverage data analytics. Lacking an in-house team, they outsourced the development of a data-driven performance monitoring tool to guide leadership decisions.
This project simulates that engagement: designing a fully functional dashboard based on mock stakeholder inputs, sample historical data, and a predefined UI layout, while also identifying additional insights not originally scoped.

Problem Statement (Background)
AtliQ Grands has been a leader in India’s premium hospitality sector for over two decades. However, due to poor strategic choices and intensified market competition, their performance has declined in key metrics like revenue growth, occupancy, and profitability.
To address this:
•	The Managing Director called for the use of Business and Data Intelligence.
•	The company lacks an internal analytics team, so they sought third-party expertise.
•	Their goal: derive actionable insights from historical booking, revenue, and operations data to help recover performance and drive strategy.

Project Goals
As the assigned Data Analyst, my objectives were to:
1.	Define Metrics
Use the metric list provided by the revenue team to calculate and implement key performance indicators (KPIs) such as RevPAR, Occupancy %, ADR, and Realisation %.
2.	Build the Dashboard
Create a fully interactive Power BI dashboard matching the mock-up provided by stakeholders, with proper layout, slicers, and data visualization elements.
3.	Extract Strategic Insights
Go beyond the dashboard to analyze patterns, identify performance gaps, and generate insightful commentary and recommendations for decision-makers.
Key Metrics Explained
Each metric was calculated and visualized using DAX formulas and appropriate data modeling techniques.
Metric	Definition
Revenue (M)	: Total booking revenue in INR millions.
RevPAR : Revenue per Available Room = Revenue ÷ DSRN.
DSRN	Daily Sellable Room Nights = Total rooms available × Days.
Occupancy %	: Percentage of sellable rooms that were booked.
ADR	Average Daily Rate = Revenue ÷ DURN.
Realisation %	: Proportion of potential revenue that was realized.
Cancellation % : 	Portion of bookings that were cancelled.
Average Rating : Guest satisfaction score based on post-stay feedback.

These metrics support operational efficiency tracking, pricing optimization, and demand forecasting.

Dashboard Design (Dynamic & Interactive)
This is a fully interactive Power BI dashboard, designed with stakeholder usability in mind. Key dynamic features include:
Time-Based Interactivity
•	Users can select any week or date range using the timeline filter at the top.
•	All visual elements (KPIs, trend charts, tables) update instantly based on selected time frames.
•	Enables week-over-week (WoW) and multi-week performance comparison.
Use Case
•	Focus on specific weeks (e.g., festival seasons or business downturns).
•	Compare pre- and post-campaign performance.
•	Drill into weekly occupancy volatility or RevPAR fluctuations.

Additional Dynamic Filters
•	City Filter – Narrow insights to specific hotel markets.
•	Room Class & Type Filters – Analyze trends by room segmentation (e.g., deluxe vs executive).
Key Features
•	✅ Dynamic, filter-responsive dashboard with real-time visual updates.
•	✅ Supports time-series comparisons across weeks and segments.
•	✅ Drill-downs by City, Room Class, and Room Type.
•	✅ Fully aligned with the stakeholder-provided UI mock-up.
•	✅ Offers strategic, data-backed insights beyond surface-level reporting.
Business Insights Generated
Beyond standard metrics, I analyzed the data to extract high-value insights:
Revenue Split Insight
•	Luxury hotels generate 61.6% of total revenue, but occupancy is lower than business hotels.
Recommendation: Introduce flexible pricing, loyalty campaigns, or bundled services to boost utilization.
Booking Behavior
•	Weekends perform better across all metrics (RevPAR, ADR, Occupancy %), suggesting a spike in leisure demand.
Recommendation: Implement dynamic pricing models that adjust rates based on day-type trends.
Platform Performance
•	Direct Online and OTA platforms yield higher realization %, while Journey and Aggregators show lower returns.
Recommendation: Negotiate better commission structures or reduce reliance on underperforming channels.
Underperforming Properties
•	Some properties in Mumbai and Bangalore show low occupancy but high ADR, suggesting poor demand matching.
Recommendation: Optimize local marketing spend and assess competitor pricing in these micro-markets.


Tools & Tech Stack
Tool: Purpose
Power BI: Main dashboard development platform.
DAX	Metric: calculation and logic building.
Power Query:	Data cleaning and transformation.
Excel/CSV:	Source data files.

Conclusion
This project reflects how data-driven storytelling with Power BI can empower a struggling business like AtliQ Grands to:
•	Identify underperformance drivers
•	Optimize pricing and platform strategies
•	Improve utilization and guest experience
•	Make informed, timely decisions with confidence
The dynamic nature of the dashboard — particularly its real-time filtering by week, city, and room category — equips AtliQ’s leadership with the agility to explore trends, detect anomalies, and drive faster business decisions in a volatile market.
