# Machine Downtime Analysis
Cover Image
# Introduction
Every day, hundreds of industrial machines operate across Daikibo's manufacturing facilities, producing thousands of components that keep production running. Behind these operations, each machine continuously generates telemetry data that captures its health and performance. While this stream of data provides a detailed view of factory operations, important questions remain: Which factories experience the most machine failures? Which machines are most prone to breaking down?

Answering these questions is essential for reducing operational downtime, improving equipment reliability, and helping maintenance teams prioritize resources where they are needed most.

As part of the analytics team supporting Daikibo, I stepped into the role of a Data Analyst tasked with analyzing one month of machine telemetry data collected from four global manufacturing facilities. By developing business-focused KPIs and an interactive Tableau dashboard, this analysis uncovers equipment failure patterns, identifies operational risks, and provides data-driven recommendations to support proactive maintenance and more informed operational decision-making.

# Problem Statement
Machine breakdowns can delay production, increase repair costs, and reduce manufacturing efficiency. Although Daikibo collects telemetry data from its manufacturing facilities every day, the company lacked a clear understanding of where equipment failures occurred most frequently and which machine types contributed most to downtime.

Without these insights, it's difficult to know where problems are happening or which machines need attention first. As a result, machines are often repaired only after they break down, leading to production delays and higher maintenance costs. By analyzing machine telemetry data, the company can identify failure patterns, address issues earlier, and keep its factories running more efficiently.

For this analysis, we’re going to focus on the questions below to get the information we need for our client -

Here are the key questions we need to answer for our client:

1. In which location did machines break the most?
2. What are the machines that broke most often in that location?


# Objective
The goal of this project is to analyze one month of machine telemetry data collected from Daikibo's four manufacturing facilities. Using Tableau, I explored the data to identify where machine breakdowns happened most often, which machines failed the most, and what patterns could help the company reduce downtime and improve maintenance planning. The goal is to turn raw machine data into clear insights that support better business decisions.

# Data Summary
This analysis draws on one month of machine telemetry data collected from Daikibo's four global manufacturing facilities in Japan, Germany, and China. The dataset, provided as part of the Deloitte Data Analytics Virtual Experience on Forage, contains telemetry records from nine machine types, with each machine reporting its operational status every 10 minutes. Before analysis, the data required minor preparation, which includes creating calculated fields to classify machine status into uptime and downtime events for KPI development and visualization in Tableau.
Check data here https://www.theforage.com/virtual-experience/io9DzWKe3PTsiS6GG/deloitte-australia/data-analytics-s5zy/data-analysis

# Methodology
## Data Import

- Imported the JSON telemetry dataset into Tableau
- Verified all schema levels during import to ensure the complete dataset was loaded

![Screenshot](tableau-datasource.png)

