# SQL-Flight-Data-Analysis-and-Reporting

# Airline Database Analysis with SQL

This project contains a series of advanced SQL queries and insights derived from a normalized airline database. It demonstrates how to use SQL for extracting business-critical insights related to flight operations, passenger behavior, aircraft utilization, and revenue analytics.

## Dataset Overview

The project uses a comprehensive **relational airline database**, consisting of the following tables:
- `flights`
- `aircrafts`
- `airports`
- `boarding_passes`
- `seats`
- `bookings`
- `tickets`
- `ticket_flights`

## SQL Use Cases & Business Questions Answered

Each query in this repository solves a specific real-world airline business problem, including:

1. **Departure Delays Analysis** – Calculate average delay for late departures.
2. **Aircraft Usage** – Count how often each aircraft is used.
3. **Revenue Tracking** – Total revenue generated per flight.
4. **Boarding Patterns** – Average boarding number per flight.
5. **Seat Occupancy & Fare Conditions** – Compare boarding passes issued vs available seats and analyze fare types.
6. **Top Revenue Flights** – Identify the highest earning flights.
7. **Flight Duration by Aircraft Model** – Find average scheduled flight times per aircraft model.
8. **Airport Activity** – Count departures and arrivals at each airport.
9. **Booking Trends** – Analyze daily bookings and revenue over time.
10. **Frequent Routes** – Discover most common travel routes.
11. **Passenger Boarding Summary** – Number of passengers per flight.
12. **Occupancy Rate per Flight** – Measure how full flights are.
13. **Fare Spend per Passenger** – Total money spent by each customer.
14. **Flight Occupancy Visualization** *(Optional in future)* – Visualize occupancy trends using BI tools.

## Skills Demonstrated

- Advanced SQL (Aggregation, Joins, Subqueries, CASE, GROUP BY)
- Relational Data Analysis
- Business Intelligence & KPIs
- Airline Operational Analytics

## Folder Structure

airline_sql_project/
 ┣ solved_analysis_queries.sql                -- All business queries
 ┣ Airlines_schema_files.sql           -- Table structures (airports, flights, etc.)
 ┣ Flight_Data_Analysis_and_Reporting     -- Questions for Queries
 ┣ README.md                  -- This file

## Tools Used

- MySQL
