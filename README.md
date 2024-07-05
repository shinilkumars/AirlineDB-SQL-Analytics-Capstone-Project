# Airline Database SQL Analytics 

![Airline](https://github.com/shinilkumars/AirlineDB-SQL-Analytics-Capstone-Project/assets/173347067/50ef4e6c-0b07-49fe-9f49-2de001512ef4)

## Project Overview
This capstone project focuses on an in-depth analysis of the Airline database using advanced SQL techniques. The project demonstrates proficiency in complex SQL queries, data manipulation, and extraction of meaningful insights from a real-world airline database schema.

## Database Schema Overview
The Airline Database contains several interconnected tables representing various aspects of airline operations:

- Bookings
- Tickets
- Ticket_flights
- Flights
- Airports
- Aircraft
- Seats
- Boarding_passes


### Entity Relationship Diagram :
![AirlineDB pdf (1)](https://github.com/shinilkumars/AirlineDB-SQL-Analytics-Capstone-Project/assets/173347067/5dc743b4-e109-4be7-ab76-9425c695b6ca)

### Key relationships:
- One booking can include several passengers, each with a unique ticket.
- A ticket includes one or more flight segments.
- Each flight goes from one airport to another.
- Aircraft models have specific seat configurations.

## Project Highlights

- Comprehensive analysis of flight data, including departures, arrivals, and cancellations.
- Exploration of aircraft utilization and performance.
- Customer-centric analysis focusing on bookings and potential refunds.
- Airport performance evaluation.

## Key SQL Concepts and Techniques Used

- **Basic SQL Operations:** Mastered fundamental SQL commands for data retrieval and manipulation.
- **Joins:** Employed various join types to combine data from multiple tables.
- **Aggregation Functions:** Applied functions to perform calculations on sets of values.
- **Advanced SQL Functions:** Leveraged sophisticated SQL functions for complex data analysis. 
  - Employed Window functions for comparative analysis within data subsets. 
  - Utilized Date and Time functions for temporal data manipulation and reporting. 
  - Implemented conditional logic for data categorization.
- **Subqueries and Common Table Expressions (CTEs):** Structured complex queries for advanced data retrieval. 
  - Created CTEs to improve query readability and performance. 
  - Developed nested subqueries to handle multi-level data aggregation and filtering.
- **String Operations:** Performed text-based data manipulation and searching.
- **Data Manipulation:** Handled various data scenarios including NULL values. 
  - Implemented strategies to manage and analyze datasets with missing information.

## Sample Queries and Insights

1. **Airport Analysis**
   - Identified airports in specific timezones
   - Analyzed airports with maximum departure flights

2. **Flight Statistics**
   - Counted flights between specific airports
   - Analyzed flight cancellations and delays

3. **Aircraft Utilization**
   - Examined seat configurations across different aircraft
   - Identified flights using specific aircraft models (e.g., Airbus, Boeing)

4. **Customer-Centric Analysis**
   - Calculated potential refunds for cancelled flights
   - Analyzed booking patterns

5. **Time-Based Analysis**
   - Identified first and last flights for each airport daily
   - Examined morning flight schedules

## Tools Used
- PostgreSQL
- pgAdmin (SQL client)

## Skills Learned and Enhanced
- Advanced SQL query construction and optimization
- Data modeling and database schema interpretation
- Complex problem-solving through SQL
- Performance tuning of SQL queries
- Data cleaning and preprocessing using SQL
- Analytical thinking and data-driven decision making
- Proficiency in pgAdmin for database management and query execution
- Understanding and manipulation of large-scale relational databases
- Time-series data analysis in SQL
- Advanced aggregation and window function techniques
- Subquery and CTE optimization for complex data retrieval
- Cross-table data analysis and relationship mapping

## SQL Query File
[Download SQL Queries](path/to/your/sql_file.sql)

Click the link above to download the SQL file containing all the queries used in this project. This file includes detailed comments explaining each query's purpose and functionality, serving as a comprehensive reference for the analytical techniques employed in this capstone project.

## Future Enhancements
- Develop visualizations based on SQL query results
- Integrate with a BI tool for dynamic reporting

## Conclusion
This project showcases advanced SQL skills in analyzing a complex airline database. Through various queries and analyses, it provides valuable insights into flight operations, customer behavior, and airport performance, demonstrating the power of SQL in data analytics for the aviation industry.
