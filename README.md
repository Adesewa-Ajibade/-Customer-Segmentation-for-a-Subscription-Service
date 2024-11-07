# Subscription Service Customer Analysis

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Column Description](#column-description)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(EDA))
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)




## Project Overview 
This project involves analyzing customer data for a subscription service  to identify segments and trends. My aim is to Understand and showcase customer behavior,, Track subscription types , and identify trends in cancellation and renewal.

## Data sources 
The dataset for this analysis was provided by Ladies in Tech Africa (LITA )_Incubator Hub , an organization for learning and training purposes. The data was provided in xlsx format, [download here](https://canvas.instructure.com/files/273182802/download?download_frd=1) making it accessible for analysis
-
## Column Description
* CustomerID: Unique identifier for each customer.
* CustomerName: Name of the customer (anonymized if necessary).
* Region: Geographical area where the customer is located (e.g., North, South, East, West).
* SubscriptionType: Type of subscription plan the customer is enrolled in (e.g., Basic, Premium).
* SubscriptionStart: Start date of the customer's subscription.
* SubscriptionEnd: End date of the customer's subscription.
* Canceled: Indicates if the subscription was canceled (TRUE or FALSE).
* Revenue: Revenue generated from the customer's subscription.
------------
## Tools Used 
* [Microsoft Excel](www.microsoft.com)-Data Cleaning, Data Analysis 
* [Microsoft SQL](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) ;[SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)- Data Querying 
* [Microsoft PowerBI](https://www.microsoft.com/en-us/download/details.aspx?id=58494)- Data Visualization
---




## Exploratory Data Analysis (EDA)
------------
Exploratory Data Analysis (EDA) based on customer data is a fundamental process that involves summarizing and visualizing customer information to uncover meaningful patterns and insights. By employing a range of statistical techniques and visualization tools, EDA facilitates the identification of customer behavior, preferences, and demographic characteristics. This analysis is critical for detecting anomalies, understanding relationships within the data, and informing strategic decision-making. Ultimately, EDA enhances the ability to develop targeted marketing initiatives and improve customer engagement and retention strategies.


### Data cleaning
------------
Excel served as the primary tool for initial data preparation, effectively addressing issues such as missing spaces and duplicates to ensure data accuracy. It was also utilized to analyze subscription patterns and calculate essential metrics, including the average subscription duration. The use of pivot tables facilitated a comprehensive analysis, allowing for:
 - **Average Subscription Duration**: Calculated average subscription duration across all customers, revealing how long customers typically remain subscribed.
 - **Subscription Patterns by Region**: Created reports summarizing subscriptions by region, helping to pinpoint regions with the highest engagement.
  

  ![Screenshot (54)](https://github.com/user-attachments/assets/2b5d35d4-55a8-4a66-97e2-cf2b1e816de6)

------------

### Data Querying 
SQL was employed to conduct data queries, providing a detailed analysis of customer trends and regional patterns. Key findings included:
- **Total Customers by Region**: Showed customer distribution across regions, identifying the top regions by number of customers.
- **Top Subscription Types by Popularity**: Identified the most popular subscription types based on customer count, adding precision to Excel’s findings.
- **Subscription Cancellations**: Highlighted customers who canceled within six months, providing insights into early-stage churn.
- **Revenue Insights**: Calculated total revenue by subscription type and discovered top revenue-generating segments.
- **Regional Cancellations**: Identified the top 3 regions for subscription cancellations, highlighting areas needing improved retention strategies.
  
----![Screenshot (46)](https://github.com/user-attachments/assets/3f46dcfe-dfb0-401f-9d25-4f9d1c8c0f3a)
![Screenshot (47)](https://github.com/user-attachments/assets/a4fe446c-9a94-4296-ab98-b15fa9204476)
![Screenshot (49)](https://github.com/user-attachments/assets/02fb419c-a1a6-4710-a8da-3d45146e41af)


--------
### Data Visualization
In Power BI, I developed a dynamic, interactive dashboard that visually communicates these insights, allowing for easy exploration. Key findings included:
- Total Number of Customers:
The dataset has 33.79K total customers. This is a substantial customer base, and we can infer that the subscription service has a wide reach.

- Total Revenue:
The total revenue generated is 68 million (68M). This indicates a healthy revenue stream, but further breakdowns are necessary to understand which customer segments contribute the most to the revenue.

- Average Subscription Duration:
The average subscription duration is 365.35 days (about a year). This suggests that most customers are subscribed for a year, which is typical in many subscription models. However, further segmentation by subscription type and region can provide more insights into retention trends.

- Total Discontinued Subscriptions:
The total number of discontinued subscriptions is 19K, which highlights a potential area of concern for the business. Investigating why these subscriptions were canceled can provide valuable insights for customer retention strategies.

- Subscription Types:
The distribution of revenue by subscription type shows that:

Basic subscriptions are generating the highest revenue, followed by Premium and Standard subscriptions.
The large revenue contribution from the Basic plan could indicate that it is the most popular or the most affordable plan, making it attractive to a wide customer base.
- Customer Distribution by Region:
The customer base is well-distributed across regions:

   - East has a slightly lower number of subscribers compared to South, North, and West, but the region shows a higher proportion of discontinued subscriptions, which might indicate a higher churn rate.
   - West has a steady number of customers, and the churn seems lower compared to the East.
- Revenue by Region:

The East region shows the highest revenue, followed by the North region, although there is a slight dip in the West and South.
Revenue is highest in East, which is significant because it could indicate where the service is performing best.
- Average Revenue by Subscription Type:

The average revenue from each subscription type is nearly equal across all three types (Basic, Premium, and Standard). This points to a balanced contribution from each subscription model but may warrant further segmentation analysis to determine where most of the growth is occurring.


![Screenshot (60)](https://github.com/user-attachments/assets/08014529-fcfc-4972-8e09-545f7deeafb7)


------------

## Recommendations
------------
1. Customer Retention: The high rate of discontinued subscriptions (19K) is a concern. It is critical to conduct further analysis to identify why customers are unsubscribing. Implementing a customer feedback mechanism and improving customer support could reduce churn. Targeting customers who have been with the service for less than a year could help improve retention.

2. Revenue Optimization: The revenue breakdown by subscription type indicates that Basic subscriptions generate the highest revenue. The company could consider expanding this plan, offering more perks or value-added services to encourage longer subscriptions. However, the Premium and Standard plans should not be neglected; tailored promotions and features could increase their adoption.
3. Regional Focus:The East region shows a high churn rate and significant revenue, but it may need more attention in terms of customer retention initiatives.
South and West regions seem stable, but increasing customer acquisition efforts in these regions may help maintain or boost growth.
The company should focus on targeted marketing campaigns in the East and North regions to increase the number of active subscriptions while reducing cancellations.

## Conclusion

The Subscription Service Customer Analysis dashboard provides a clear and detailed view of the current subscription landscape. The company has a solid customer base and a significant revenue stream, but customer retention needs attention, particularly in the East region where cancellations are higher. The Basic subscription plan is a strong revenue driver, but the Premium and Standard plans should be further explored for growth opportunities.

This Dashboard helps identify patterns, trends, and potential areas of improvement, allowing the company to refine strategies for customer engagement, retention, and revenue maximization. By focusing on these key areas, the company can continue to grow its subscriber base while improving overall customer satisfaction.






