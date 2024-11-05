# -Customer-Segmentation-for-a-Subscription-Service

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Column Description](#column-description)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data--analysis-(eda))
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
- **Sales Overview**: A high-level view of total subscriptions, cancellations, and revenue, showing overall performance trends.
- **Customer Segmentation**: An analysis of customer behavior across segments, including active and canceled subscriptions.
- **Regional Trends and Cancellations**: Breakdown of regions with high cancellation rates, displayed with interactive visuals to emphasize trends.
- **Time-Based Insights**: Monthly sales and cancellation trends were visualized to show seasonality in customer behavior.

------------

## Recommendations
------------
1. **Target High-Cancellation Regions**: Focus retention efforts on regions with high cancellation rates to improve customer retention.
2. **Promote Popular Subscription Types**: Invest in marketing the most popular subscription types to attract new customers.
3. **Analyze Short-Term Cancellations**: Examine factors influencing cancellations within the first six months to identify improvement opportunities in early customer engagement.

## Conclusion

The analysis gives useful information on how customers act, what they like, and trends in different areas. Key findings show that customers in each region have different needs, prefer various products, and have specific characteristics that affect what they buy. Overall, this analysis of customer data highlights the need to focus on the customer. Adjusting strategies to meet the unique needs of each customer group will help the company succeed, stay in tune with changing customer expectations, and stay competitive in the market.









