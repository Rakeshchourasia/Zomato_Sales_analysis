Zomato Sales Analysis Using SQL and Power BI

This project involved analyzing Zomato restaurant data using Excel, SQL, and Power BI to uncover trends and insights. The aim was to explore the data, perform meaningful analysis, and create interactive visualizations that provide a deeper understanding of the restaurant industry.

Objectives

📊 Data Preparation

Country Map Table: Created a table to facilitate geographical analysis.

Calendar Table: Built using the datekey column with details such as:

Year, Month Number, and Full Month Name

Quarter (Q1, Q2, Q3, Q4)

Year-Month Format (YYYY-MMM)

Weekday Number and Name

Financial Month (April = FM1, May = FM2, ..., March = FM12)

Financial Quarter (based on Financial Months)

🔍 Data Analysis

Counted the number of restaurants by city and country.

Tracked restaurant opening trends by year, quarter, and month.

Categorized restaurants by average ratings.

Grouped restaurants into average price range buckets and analyzed their distribution.

Measured the percentage of restaurants offering table booking and online delivery options.

📈 Visualization

Created dynamic dashboards to highlight:

Cuisine preferences

Rating patterns

City-specific trends

Other key metrics

Tools and Techniques

🟢 Excel

Excel was essential for initial data analysis and preparation:

Data Summarization:

Used SUMIFS and COUNTIFS to calculate values based on specific conditions.

Created PivotTables and PivotCharts for flexible data exploration.

Highlighting Trends:

Applied conditional formatting to emphasize critical data points.

Data Integration:

Merged tables with VLOOKUP and INDEX-MATCH functions.

Date Manipulation:

Extracted insights using functions like DATE, YEAR, and TEXT.

Interactive Reports:

Linked slicers to multiple PivotTables for easy filtering.

🟢 SQL

SQL was used to efficiently extract and process data:

Basic Queries:

Retrieved and filtered data using SELECT, FROM, and WHERE clauses.

Grouping and Sorting:

Organized data with GROUP BY and sorted results with ORDER BY.

Applied HAVING to filter aggregated results.

Advanced Functions:

Used window functions like ROW_NUMBER, RANK, and DENSE_RANK to rank and segment data.

Leveraged date functions (DATEADD, DATEDIFF, DATEPART) for time-based analysis.

🟢 Power BI

Power BI was the primary tool for creating interactive dashboards:

Data Modeling:

Built relationships between tables and added calculated columns for better insights.

Advanced Calculations:

Created measures using DAX formulas to calculate metrics like average ratings and price ranges.

Visual Storytelling:

Designed maps, charts, and tables to visualize data effectively.

User Interaction:

Added slicers and filters for dynamic exploration and drill-through features for detailed analysis.

Key Insights

🌍 Geographical Trends: Identified the cities and countries with the most restaurants.

📅 Opening Patterns: Discovered seasonal and time-based trends in restaurant openings.

⭐ Customer Preferences: Analyzed ratings and popular cuisines.

📊 Operational Insights: Calculated the share of restaurants offering table bookings and online delivery.

💰 Price Ranges: Explored how restaurants are distributed across various price ranges.

Conclusion

This project demonstrates how Excel, SQL, and Power BI can work together to analyze and visualize data effectively. The insights and dashboards created during this analysis provide actionable information that can help stakeholders make informed decisions about the restaurant industry.
