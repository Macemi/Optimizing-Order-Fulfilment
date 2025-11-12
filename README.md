# Optimizing-Order-Fulfilment
This project focuses on optimizing order fulfillment using a data-driven approach through the development of an interactive Excel dashboard to eliminate mounting order backlogs, improve visibility, reduce costs, and enhance customer satisfaction.

## Table of Contents
- [Project Overview](#project-overview)
- [Business Challenge](#business-challenge)
- [Data Source](#data-source)
- [Tools](#tools)
- [EDA](#eda)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)

- ## Project Overview
Streamline Logistics Solutions is a distinguished and long-standing player in the supply chain and logistics industry, with a rich history dating back over two decades. The company has built its reputation on a commitment to delivering exceptional service, characterised by the swift and dependable delivery of a wide array of products to customers nationwide.

This project focuses on **optimising order fulfilment** using a **data-driven approach** through the development of an **interactive Excel dashboard** to eliminate mounting order backlogs, improve visibility, reduce costs, and enhance customer satisfaction.

<img width="1657" height="664" alt="Screenshot 2025-11-12 090713" src="https://github.com/user-attachments/assets/24a0982c-56b5-4f76-ac91-80f8f9a5c839" />

## Business Challenge
Streamline Logistics Solutions is facing several critical operational challenges:

- **Mounting Order Backlogs**: Current routing and resource allocation processes are causing a growing backlog of orders.
- **Visibility Gap**: No real-time updates on customer order progress.
- **Customer Frustration**: Increased frequency of customer complaints regarding delayed deliveries.
- **Escalating Costs**: Operational expenses on the rise due to overtime payments and expedited shipping to clear order backlogs.

- ## Data Source
- Delivery Data: The primary dataset used for this analysis is the "Deliverydata.csv" file, containing information about the delivery.

## Tools
- **Microsoft Excel** – For data cleaning, analysis, pivot tables, and building interactive dashboards
- **Excel Charts & Slicers** – For dynamic visualizations and user interactivity
-  **Office Script** - For automating the process like auto-generating KPIs



## EDA
*(Exploratory Data Analysis inferred from dashboard visuals and insights)*

- Analyzed **order completion status**, **delivery timelines**, and **backlog percentage**
- Segmented data by:
  - Delivery routes
  - Drivers
  - Vehicle types
  - Cities
  - Day of week / hour
  - Order rules (Standard, Custom, Expedited)
- Explored correlations between **delays**, **negative feedback**, and **operational factors**


## Data Analysis
An interactive dashboard was created to monitor and analyze order fulfillment performance:

### **Analysis Dashboard **
- Order status overview (In Progress: 767, Completed: 733)
- Order tracking timeline by hour
- Average delay by route, city, driver, and vehicle
- Top 10 drivers based on average delay
- Customer feedback distribution (35% Negative)

### **Analysis Dashboard **
- Total drivers (1,500), backlog % (51.13%), negative feedback % (35.27%)
- Order delivery time trends by hour and day of week
- Backlog count by city and route
- Average delay by feedback type

## Results and Findings
### Key Performance Insights

#### Overall Performance
- **Over 51% backlog** — significant delay in order completion.
- **Average delay across all orders**: ~**14.51 minutes**
- **Expedited Rules** have the **highest delay at 15.0 mins**, contrary to their intended purpose.
- **High negative feedback of 35%** correlates with delivery delays and inefficiencies.

#### Underperforming Resources
- Drivers **D86, D44, and D29** have significantly higher average delays and consistently underperform.
- **Route3, Route1, and Route2** consistently show higher delays.
- **CityE** has the highest average delay at **15.29 mins**.
- **"Bike C"** deliveries have higher delays compared to **"Van A"** (best at **14.15 mins**).

#### Top Performers
- **Route5** performs best with **13.69 mins** average delay.
- **CityD** is the most efficient at **14.09 mins**.
- **Van A**: Best vehicle performance at **14.15 mins**.

---

## Recommendations

1. **Reduce backlog** by optimizing underperforming drivers and reviewing high-delay routes. Allocate personnel or automation to clear the backlog.
2. **Review logic and impact of ‘Expedited Rules’**, which have the highest delay (15 mins).
3. **Conduct performance reviews, interviews, and training** for underperforming drivers (**D86, D44, D29**) and consider reassignments or interventions.
4. **Improve delivery experiences in CityE and Route3/1/2**, which drive most delays.
5. **Customer satisfaction strategy** should target reasons for negative feedback, especially where delays are less apparent (e.g., packaging, communication).
6. **Conduct traffic flow studies**, adjust delivery windows, or reallocate delivery zones for **Route1, Route2, and Route3**.
7. **Reassess operational efficiency and suitability of Bike C** for deliveries.
8. **Launch a targeted customer feedback initiative post-delivery**. Use SMS/email surveys and incentivize participation with discounts or priority service.









