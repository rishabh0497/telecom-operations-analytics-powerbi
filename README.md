\# Telecom Operations Analytics Dashboard | Power BI



\## Overview

This project is an interactive Power BI dashboard built using simulated telecom customer support data. It is designed to monitor operational performance, evaluate service efficiency, and support data-driven decision-making across different levels of the business.



The dashboard provides visibility into overall performance, interval-level trends, and agent/team-level insights, making it suitable for operations managers, team leads, and analysts.



\---



\## Business Objective

The goal of this project is to demonstrate how data analytics can be used to monitor and improve customer service operations in a telecom environment.



It focuses on:

\- Tracking service demand vs forecast

\- Identifying inefficiencies in handling time and abandonment

\- Enabling drill-down analysis for deeper investigation

\- Supporting agent and team performance evaluation



\---



\## Key Metrics

\- Calls Answered

\- Actual vs Forecast %

\- Abandoned %

\- Average Handle Time (AHT)

\- Number of Surveys

\- NPS Score

\- CSAT Score

\- Transfer %



\---



\## Dashboard Structure



\### 1. Global Performance View

Provides a high-level overview of call centre performance.



Includes:

\- KPI summary cards with previous year comparison

\- Daily performance trends

\- Department-level call distribution

\- AHT vs Abandonment analysis

\- Dynamic filters (Year, Month, Department)



\---



\### 2. Interval Drill-Through View

Allows deeper analysis of a selected day at an interval level.



Includes:

\- Calls handled by interval

\- AHT and Abandonment trends throughout the day

\- Tabular breakdown for detailed inspection



Use case:

Helps identify peak load times and operational bottlenecks.



\---



\### 3. Agent \& Team Performance View

Designed for performance monitoring and coaching.



Includes:

\- Agent and Team Manager filters

\- KPI comparison (current vs previous year)

\- AHT, NPS, CSAT trends over time

\- Dynamic “last N months” view



Use case:

Supports team leaders in identifying performance gaps and coaching opportunities.



\---



\## Data Model

The dashboard follows a star schema approach with separate fact and dimension tables:



\*\*Fact Tables\*\*

\- FactCalls

\- FactAbandoned

\- FactForecast

\- FactSurveys



\*\*Dimension Tables\*\*

\- Agents

\- Departments

\- Calendar

\- Time



This structure enables efficient filtering, scalability, and clean DAX calculations.



\---



\## Tools \& Technologies

\- Power BI

\- Power Query (Data Transformation)

\- DAX (Measures \& Calculations)

\- Excel / CSV (Simulated Data Sources)



\---



\## Key Features

\- Interactive slicers for flexible analysis

\- Drill-through functionality for detailed exploration

\- Year-over-year comparisons

\- Dynamic KPI cards with contextual insights

\- Clean and structured data model

\- User-friendly dashboard layout



\---



\## Screenshots



\### Global View

!\[Global View](screenshots/global-view.png)



\### Interval Drill-Through View

!\[Interval View](screenshots/interval-view.png)



\### Agent Performance View

!\[Agent View](screenshots/agent-view.png)



\### Data Model

!\[Data Model](screenshots/data-model.png)



\---



\## How to Use

1\. Download the `.pbix` file from this repository

2\. Open it in Power BI Desktop

3\. Use slicers to filter by time, department, agent, or team

4\. Click on a specific date to drill through into interval-level analysis

5\. Explore agent performance using the Agent View



\---



\## What I Learned

Through this project, I strengthened my skills in:

\- Designing a scalable data model in Power BI

\- Writing DAX measures for operational KPIs

\- Implementing drill-through navigation

\- Building dynamic and interactive dashboards

\- Translating business requirements into analytical solutions



\---



\## Limitations

\- The dataset used in this project is simulated

\- The business context and branding are fictional

\- Metrics are designed for demonstration purposes and may not reflect real-world complexities



\---



\## Author

Rishabh Dua



\---



\## Note

This project is part of my analytics portfolio and is intended to showcase my skills in Power BI, data modelling, and business intelligence. It does not represent any real company or dataset.

