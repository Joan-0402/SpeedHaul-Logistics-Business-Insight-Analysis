# SpeedHaul-Logistics-Business-Insight-Analysis
This project aims to demonstrate how data analytics can be effectively utilized to improve business performance.

1. Project Overview

This project demonstrates how data analytics can be used to improve logistics and fleet performance at SpeedHaul Logistics. By analyzing delivery, fuel, and customer satisfaction data, we aim to answer:

  - How SpeedHaul can optimize delivery scheduling?
  - What strategies can improve fleet utilization?
  - How the company can enhance customer experience through real-time insights?

2. Data Understanding

The dataset contains 100 records of delivery operations with the following fields:

  Fields:  Delivery ID, Truck ID, Route (KM), Avg Delivery Time (Hrs), On-Time?, Fuel Cost (GHS), Client Satisfaction (1–5), Packages Delivered


3. Methodology

Excel → Data cleaning and preparation

 - Removed inconsistencies in truck IDs and route entries

 - Ensured numeric fields were properly formatted

 - Handled missing values and duplicates 

Power BI → Analytics and Visualization

 - Built interactive dashboards for fleet efficiency, costs, and customer experience

 - Created DAX measures for KPIs (on-time delivery %, fuel efficiency, satisfaction score)

4. Dashboard

The Power BI dashboard highlights:

Key Metrics

 - Average Delivery Time (Hrs): 3.58 
 - On-Time Delivery Rate: 63.11%
 - Total Deliveries: 100
 - Average Route Distance: 123 km
 - Correlation (Route vs Time) 0.98 (Strong Positive)

<img width="1293" height="697" alt="image" src="https://github.com/user-attachments/assets/f5c7d364-14ac-4e2e-b136-6eed23a3c359" />


5. Key Insights
   
 - Trucks with longer routes tend to have lower on-time performance and higher fuel costs, with some short routes also experiencing delays due to inefficiencies or delays unrelated to distance (e.g., traffic, driver behavior, stop frequency).
 - Client satisfaction drops sharply when deliveries are late, even if packages are delivered successfully
 - A small number of trucks handle most deliveries (TRK102 and TRK108), indicating uneven utilization across the fleet.
 - Significant variation in fuel consumption across trucks, indicating maintenance or driving behavior issues.


6. Recommendations

 - Reduce delays on short routes using mapping and delivery logs.
 - Reassign routes to trucks with lighter workloads.
 - Implement real-time GPS or SMS delivery updates for customers.
 - Track KPIs through dashboards to monitor delivery times, on-time performance, and truck utilization.
 - Track truck performance to prevent breakdowns and improve fuel efficiency.

7. Conclusion

This project illustrates how data analytics in logistics can uncover inefficiencies, reduce costs, and enhance customer experience. With actionable insights, SpeedHaul can optimize fleet utilization, strengthen operational efficiency, and improve customer retention.

8. Tools & Tech Stack

Excel → Data cleaning & preprocessing

Power BI → Data modeling & dashboard creation

DAX → Custom KPIs and measures


