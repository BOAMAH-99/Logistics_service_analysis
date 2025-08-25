# Logistics_service_analysis
This analysis examines delivery operations and customer experience in a logistics dataset. The objective is to uncover patterns in delivery delays, fleet utilization, and client satisfaction, and evaluate their impact on efficiency and costs. By analyzing delivery times, truck usage, route distances, and customer feedback, this study highlights inefficiencies and provides data-driven insights to optimize fleet scheduling, improve timeliness, and enhance overall service quality.

## Objective: To identify patterns in delivery delays, fleet utilization, and customer satisfaction, and use these insights to recommend strategies that improve operational efficiency, optimize resource usage, reduce costs, and enhance the customer experience

## Key Features
- Power BI (Interactive dashboard)
- Powerpoint Slides

## Dashboard
[View the interactive Power BI dashboard](https://github.com/BOAMAH-99/Logistics_service_analysis/blob/main/Dashboard/Three%20Logistics%20Dashboard.pbix)

or view below:

<iframe title="UK TRAINS ANALYSIS DASHBOARD" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=ed853100-e602-41c8-a42c-58a1b429a2ab&autoAuth=true&ctid=bd697c1b-c481-479c-841e-c618542675c3" frameborder="0" allowFullScreen="true"></iframe>

## Tools and Skills Used
Power BI (interactive Dashboards, DAX, visuals, KPIs)
Excel (Statistical Analytics)
Data Cleaning & Exploratory Data Analysis (EDA)


## Delivery and Truck Performance Analysis
Differences in Truck Usage: 
- There are considerable differences in delivery distances, fuel costs, and distances covered by each truck, indicating some trucks are underused or inefficiently allocated.

Truck Performance:
- Truck TRK108 delivers the best overall performance, likely due to efficient routing, better utilization, or driver behavior.
- Truck TRK105 performs the worst, suggesting the need for review or intervention to improve its efficiency.

Impact of Delivery Distance on Time: 
- Longer delivery distances correlate with increased delivery times, naturally due to travel time and possibly route complexity.

Client Satisfaction:
- Increased delivery times negatively impact client satisfaction, leading to lower client satisfaction scores (3 or below).
- Specifically, deliveries taking longer than 4.59 hours or covering more than 165 kilometers trigger negative client reactions.
- Overall, client satisfaction scores tend to decrease as delivery time and distance increase, highlighting the importance of optimizing routes and improving delivery speed

## Strategic Recommendations
Optimize Truck Allocation:
- Review utilization rates of all trucks to identify underused vehicles.
- Redistribute workloads to balance usage effectively and enhance overall fleet efficiency.

Leverage Best Practices from TRK108:
- Investigate the successful practices, routes, and driver behaviors of TRK108.
- Implement these strategies on less efficient trucks, especially TRK105, to boost performance.

Route and Time Management:
- Employ route optimization tools to minimize delivery distance and time.
- Monitor real-time traffic conditions and vehicle locations.
- Schedule deliveries dynamically for optimal efficiency and customer satisfaction.

Client Satisfaction Monitoring:
- Use key thresholds, deliveries over 4.59 hours or 165 km as triggers to flag potential risks to client satisfaction.
- Prioritize flagged deliveries for enhanced communication and proactive management.

Technology Integration:
- Integrate Samsara for real-time monitoring of:
  - Distance covered
  - Deliveries completed
  - Delivery times
  - Fuel consumption per truck
    This data should feed into a live dashboard accessible by management for timely decisions.
- Combine delivery distance data with real-time GPS and live mapping to adapt delivery schedules dynamically, enabling efficient trip planning and quick responses to delays.

Truck Suitability:
- Designate TRK108 for long-distance deliveries due to its superior fuel efficiency and overall performance metrics.

Delivery Prioritization and Client Incentives:
- Flag all deliveries surpassing 165 km or 4.59 hours ETA.
- Apply prioritization protocols, bolster client communication during these deliveries, and introduce distance-based loyalty incentives such as distance per km after 165km to encourage repeat business and improve client tolerance.

Enhanced Delivery Time Prediction and Client Communication:
- Build a system integrating advanced route planning tools like OptimoRoute or Routific.
- Improve accuracy of delivery time predictions.
- Provide clients with live tracking access and real-time notifications to boost confidence and transparency





