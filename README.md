# Call_Center_Dashboard_Power-Bi

 Overview*

The *Call Centers Dashboard* is an interactive Power BI report that provides real-time and historical insights into call center operations. It enables managers and decision-makers to monitor call volumes, resolution rates, agent efficiency, and customer satisfaction to ensure optimal service delivery.


Objectives*

* Track call volumes by day, week, and month.
* Measure *First Call Resolution (FCR)* rates.
* Evaluate *Average Handling Time (AHT)* and service level performance.
* Identify peak call hours and seasonal trends.
* Compare performance between agents, teams, or locations.
* Improve *Customer Satisfaction (CSAT)* and *Net Promoter Score (NPS)*.

 Data Sources*

| Source Name       | Type                   | Description                                                                |
| ----------------- | ---------------------- | -------------------------------------------------------------------------- |
| Call Logs         | CSV / Excel / Database | Detailed record of each call (date, duration, status, agent ID, call type) |
| Agent Information | Excel / Database Table | Agent names, roles, team assignments                                       |
| Customer Feedback | CSV / Survey Data      | Customer satisfaction scores, comments                                     |

* *Data Period:* (Example: Jan 2024 – Jul 2025)
* *Update Frequency:* (Example: Daily refresh)
* *Data Privacy:* All sensitive customer data anonymized.



 Data Processing & Modeling*

* *Data Cleaning:* Removed duplicates, fixed incorrect timestamps, standardized call types.
* *Transformations:*

  * Split date/time into separate columns for better time intelligence.
  * Categorized calls by type (Inbound, Outbound, Complaint, Inquiry).
  * Created a *Date Table* for DAX time-based calculations.
* *Data Model:*

  * *Fact Table:* FactCalls (contains all call transactions)
  * *Dimension Tables:* DimAgents, DimDates, DimCallTypes, DimCustomers



 Key Metrics & KPIs*

* *Total Calls:* Total inbound & outbound calls.
* *Answered vs. Missed Calls:* Service level compliance.
* *First Call Resolution (FCR):* Percentage of calls resolved on first contact.
* *Average Handling Time (AHT):* Average duration of calls in minutes.
* *Customer Satisfaction (CSAT):* Based on post-call surveys.
* *Call Abandonment Rate:* % of calls disconnected before being answered.
* *Agent Performance:* Calls handled per agent, resolution rate, AHT comparison.

 Dashboard Pages*

*Overview Page:*

   * High-level KPIs for total calls, average handle time, CSAT.
   * Trend charts for call volume.

*Agent Performance:*

   * Ranking of agents by total calls handled and resolution rate.
   * Filter by team/shift.

 *Call Trends:*

   * Heatmap of calls by day/hour to identify peak times.
   * Seasonal trends analysis.

*Customer Satisfaction:*

   * CSAT score trend line.
   * Breakdown by call type and resolution status.

 Technical Stack*

* *Tool:* Power BI Desktop (Version X.X)
* *Languages:* DAX, Power Query (M Language)
* *Data Connection:* Import Mode (or DirectQuery if applicable)
* *Custom Visuals:* KPI Cards, Matrix Tables, Line & Clustered Column Charts, Heatmaps

 Usage Instructions*

1. Install *Power BI Desktop* (Version X.X or higher).
2. Open call centers dashboard.pbix in Power BI Desktop.
3. If applicable, update data source credentials via *Transform Data → Data Source Settings*.
4. Click *Refresh* to load latest data.
5. Use slicers and filters to interact with visuals.



Example Insights*

* "Mondays between 10 AM – 12 PM have the highest call volumes; staffing should be increased during these hours."
* "Agent ID 103 consistently resolves over 90% of calls in under 5 minutes."
* "Customer satisfaction drops significantly for calls exceeding 12 minutes."




 Future Enhancements*

* Add real-time streaming dataset for live monitoring.
* Integrate chatbot support analysis.
* Add predictive modeling for call volume forecasting.

 Author & Contact*

*Author: Komal Deshmukh
*Email:komaldeshmukh7385@gmail.com


