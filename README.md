# Syntecxhub_Railway-Ticket-Sales-Operational-Performance-Analysis
 Railway Ticket Sales & Operational Performance Analysis

 **Project Overview**
 
This project analyzes railway ticket sales data to evaluate revenue performance, passenger behavior, operational reliability, and refund impact.

The objective is to answer key business questions:

What is happening in this railway business?

Where is revenue coming from?

How reliable are operations?

How do delays affect refunds and financial performance?

Where should management focus?

The analysis was conducted entirely in Python, combining data cleaning, exploratory analysis, visualization, and business interpretation.

 **Tools & Libraries**
 
Python
Pandas
NumPy
Matplotlib
Seaborn

 **Data Cleaning & Preparation**

Before analysis, the dataset was cleaned and validated:

Standardized column names for consistency

Converted date and time columns to proper datetime format

Replaced missing railcard values with "No Railcard"

Replaced missing reason_for_delay values with "No Delay"

Verified no duplicate transaction_id values

Ensured correct data types for numerical and categorical variables

Cross-validated summary statistics to confirm data integrity

This ensured accurate calculations and reliable insights.

 **Exploratory Data Analysis**

 **Revenue & Sales Performance**
Total Revenue: $741,921
Average Ticket Price: $23.44
Revenue is concentrated in major stations such as:
Manchester Piccadilly
London Euston
Liverpool Lime Street
Credit Card is the most frequently used payment method (19,136 transactions)

**Insight:**
Revenue is driven by high-traffic stations and standard payment methods, highlighting strong urban route dependency.

 **Customer & Ticket Insights**
 
Most Purchased Ticket Type: Advance (17,561 tickets)

Most Used Ticket Class: Standard (28,595 tickets)

Average Ticket Price by Class:

First Class: $48.86

Standard: $20.72

Average Ticket Price by Railcard:

No Railcard: $27.43

Senior: $10.58

Adult & Disabled railcards show discounted spending patterns

**Insight:**

Passengers strongly prefer Standard class and Advance tickets. Railcard discounts significantly reduce average revenue per journey.

 **Journey Performance Analysis**
 
On-time Journeys: 92.76%

Delayed Journeys: 7.24%

Average Delay (Delayed Journeys Only): 42.21 minutes

Overall Average Delay: 3.25 minutes

Peak Travel Period: Morning

**Insight:**

Operational punctuality is strong overall. However, when delays occur, they are significant in duration, indicating room for improvement in disruption management.

 **Refund & Revenue Impact**
 
Refund Requests: 1,118 journeys

Refund Rate by Journey Status:

Cancelled: 30.43%

Delayed: 23.82%

On-Time: 0%

Revenue Linked to Refunded Tickets: $38,702

**Insight:**

Refunds are directly tied to service disruptions. While refunds represent a small portion of total transactions, operational inefficiencies clearly increase financial exposure.

 **Key Business Insights**
 
Revenue Concentration Risk

Major stations and Standard class tickets generate most revenue, creating dependency on high-traffic routes.

Operational Reliability Drives Financial Stability

Delays and cancellations significantly increase refund likelihood.

Discount Structures Impact Revenue Per Passenger

Railcard holders pay substantially less on average, affecting revenue optimization strategies.

 **Recommendations**
 
Improve delay response strategies to reduce refund-related revenue loss.

Monitor peak morning demand to optimize scheduling and staffing.

Develop targeted upselling or loyalty strategies for railcard holders.

Continuously monitor refund patterns as an operational performance indicator.

 **Business Conclusion**
 
The railway system demonstrates strong revenue performance and high punctuality rates. However, operational disruptions directly impact customer refunds and financial outcomes.
Improving delay management and optimizing pricing strategies could further strengthen revenue retention and customer satisfaction.
