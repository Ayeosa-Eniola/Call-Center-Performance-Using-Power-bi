# Call-Center-Performance-Using-Power-bi

## Table of Content
## Description
This project is an in-depth call center performance analysis using Power BI. It provides key insights into call center operations by tracking total calls made, call reach rates, deals closed, and revenue generated. The dashboard helps businesses identify areas for improvement, optimize agent performance, and make data-driven decisions to enhance customer engagement and sales conversions.
With interactive visualizations and dynamic filtering options, users can analyze call center performance across different time periods and identify trends that impact business growth. The project applies Power Query for data cleaning, DAX for calculations, Power BI modeling for relationships, and visualization techniques to create a comprehensive report.
## Project Overview
In this project, I created an interactive Power BI dashboard to analyze call center operations and performance. The dashboard provides insights into total calls made, call reach rates, deals closed, and total deal values to help businesses optimize their customer engagement and sales processes.

A well-managed call center plays a crucial role in customer acquisition, service delivery, and revenue generation. However, without data-driven insights, it is difficult to track key performance indicators (KPIs) and identify areas for improvement. This project aims to bridge that gap by using Power BI to turn raw data into actionable insights.
## Aims and Objectives
### Aims:

- To analyze call center operations using Power BI to identify performance trends.

- To provide a data-driven approach for improving agent efficiency and business decisions.

- To help businesses increase deal closure rates and revenue through informed decision-making.

### Objectives:

- Track overall call center performance by analyzing total calls, calls reached, and deal closure rates.

- Identify performance trends over time using filters for weekday, month, quarter, and year.

- Compare performance over different time periods to evaluate growth or decline.

- Understand agent performance by analyzing individual call reach rates, dropped calls, and deals closed.

- Provide recommendations based on data insights to help improve call center efficiency.

## Business Problem
Call centers handle thousands of customer interactions daily. However, without a structured way to track these interactions, businesses face challenges such as:

- Low call reach rates: A high number of calls made does not always translate to successful conversations with customers.

- Inefficient deal closure processes: Some agents close fewer deals despite high call volumes.

- Lack of performance tracking: Managers may struggle to monitor which agents perform well and who needs additional training.

- Poor revenue optimization: Without analyzing call success rates and deal values, businesses may be missing out on revenue opportunities.

This dashboard is designed to solve these problems by providing a clear and data-driven approach to call center management.

## Data Analysis Procedure
1. Data Collection     
   - The data source is from kaggle.
     
   - The dataset contains information on total calls, call reach rates, deals closed, and deal values.

   - Data is categorized by agents, days of the week, and overall call center performance.

1. Data Cleaning and Transformation (Power Query)

   - Handled missing values, duplicates, and data inconsistencies.

   - Converted date/time formats for accurate analysis.

   - Categorized calls into successful, dropped, and converted calls for better insights.

2. Data Modeling (Power BI Relationships & Measures)

   - Established relationships between data tables to ensure a structured analysis.

   - Created calculated columns and measures for key metrics such as total calls, call reach percentages, and conversion rates.

3. Data Analysis (DAX Calculations)

   - Used DAX (Data Analysis Expressions) to create custom calculations.

   - Computed Key Performance Indicators (KPIs) such as:

   - Call Reach Rate (%) = (Total Calls Reached / Total Calls Made) * 100

   - Deal Closure Rate (%) = (Total Deals Closed / Calls Reached) * 100

   - Total Revenue from Deals

4. Data Visualization (Power BI Dashboard)

   - Created an interactive dashboard with:

   - KPI Cards for quick insights into performance.

   - Bar Charts to compare total calls and call reach rates across different days.

   - Tables to track individual agent performance.

   - Filters to allow analysis by week, month, and quarter.
  
## Tools Used
- Power BI Visualization – For building interactive reports and dashboards.

- Power Query – For data cleaning and transformation.

- DAX Calculations – For creating custom metrics and calculations.

- Power BI Data Modeling – For establishing relationships between tables.

- Excel  – For initial data processing before importing into Power BI.

## Key Insights from the Dashboard
1. Total Calls vs. Calls Reached

   - The total number of calls made was 37,000, but only 15,000 were successfully reached.

   - This means the call reach rate was approximately 40%, indicating potential challenges in customer engagement.

2. Deals Closed and Revenue Performance

A total of 7,000 deals were successfully closed, meaning 46.7% of calls reached led to a deal.

The total deal value was 1.38 million, showing the financial impact of successful calls.

Day-wise Call Center Performance

Monday had the highest call volume (8,340 calls), but Thursday had the best call reach success rate.

Wednesday had the lowest call activity, which might indicate a lower customer response rate on that day.

Agent Performance Trends

Some agents made a high number of calls but closed very few deals, suggesting a need for training or strategy improvements.

A few top-performing agents contributed to the majority of closed deals.

Recommendations for Improvement
Increase Focus on High-Conversion Days

Since Thursday had the highest success rate, managers should increase call activities on this day to improve deal closures.

Improve Call Reach Rate

The 40% success rate means that more than half of the calls made do not reach customers.

Strategies such as better customer engagement methods, call timing optimization, and improved lead qualification can help.

Agent Training and Performance Optimization

Agents with low deal closure rates despite high call volumes should receive training on sales techniques and customer engagement.

Performance tracking should be conducted weekly to identify struggling agents early and provide necessary support.

Optimize Call Schedules

Calls on low-performance days like Wednesday should be reviewed to determine whether rescheduling or targeting different customer segments would be beneficial.

Conclusion





