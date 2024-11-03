#  National Rail UK Ticket Data Analysis (Jan - Apr 2024)


In this project, I analyzed mock train ticket data for National Rail UK to provide actionable insights into travel patterns, peak times, and revenue drivers. Using data visualization and advanced DAX functions, 
I identified the most popular routes, peak travel times, and how revenue varied across ticket types and classes. I also evaluated on-time performance metrics, identifying key factors impacting punctuality. 
This analysis equips decision-makers with a clearer understanding of high-demand routes and periods, revenue optimization opportunities, and areas for improving service reliability.

## Acknowledgements

 - [mavenanalytics Dataset](https://mavenanalytics.io/data-playground?page=2&pageSize=5)


## Discovering and Presenting Insights:
To uncover  insights, I employ a mix of exploratory data analysis (EDA), statistical methods, and data visualization techniques. Here's how I approach each goal:
###	Popular Routes Analysis:
Using aggregation and filtering techniques, I identify the routes with the highest ticket sales. Visualizations such as bar charts and Chord make it easy to see the most travelled routes.
###	Peak Travel Times:
Time series analysis and peak detection algorithms help me determine the busiest travel times. I use line graphs to present these findings clearly.
###	Revenue Analysis:
By segmenting the data based on ticket types and classes, I perform comparative revenue analysis. Pie charts, Scatter plot and stacked bar charts are used to visualize the revenue distribution.
###	On-Time Performance Diagnosis:
I analyse delay data, categorize reasons for delays, and measure their impact on service. Pie charts, stacked bar charts, and dashboard elements provide a comprehensive view of on-time performance and its contributing factors.





## Key insights:

### Popular Routes Analysis
The route between Manchester Piccadilly and Liverpool Lime Street is the most popular, indicating high passenger traffic between these two cities with an Outbound of 4,628 and of Inbound 3,002 passengers, 
closely follow by London Euston to Birmingham with 4209, but only 125 inbound, coming third is London kings cross to York with an Outbound of 3922 and no inbound.
The bar charts show the three most popular routes.

### Peak Travel Times:

##### Morning Travel Surge:
The morning period emerged as the busiest time of the day, with 11,709 out of 31,653 total travelers, accounting for approximately 37% of the daily passenger volume. 
This substantial morning surge is indicative of a strong commuter base, likely consisting of professionals and students heading to work or school. 
This insight suggests a need for increased train frequency and capacity during the morning hours to accommodate the high demand.
##### Evening Travel Patterns: 
Following the morning peak, the evening period recorded the second-highest passenger volume with 7,497 travelers. 
This reflects a typical return journey pattern for the same commuter base observed in the morning. 
The evening peak underlines the importance of providing adequate service and minimizing delays to ensure a smooth and reliable journey home for passengers.
##### Afternoon and Night Travel Trends:
Afternoon travel saw 6,425 passengers, while the night period recorded 6,022 travelers. 
These figures, although lower than morning and evening peaks, still represent significant travel volumes.
Afternoon travel might include off-peak commuters, leisure travelers, and errand-runners, while night travel could be attributed to late-shift workers, evening events, or intercity travelers.
Understanding these patterns can help in designing flexible service schedules that cater to varying passenger needs throughout the day.
##### Hourly Travel Insights:
A more granular analysis of travel times within peak periods reveals that 6 PM recorded the highest number of travelers with 3,113, closely followed by 6 AM with 3,112 travelers. 
The proximity in these figures is intriguing and suggests a balanced demand for services at the start and end of a typical workday.
This relationship indicates that the demand for train services is almost equally critical in the early morning as it is in the early evening.

### Revenue Analysis:
An analysis of revenue generation by ticket class for National Rail reveals significant insights into the financial dynamics of the service. 
Despite first class tickets constituting only 9% of total ticket sales, they contribute a notable 20% to the overall revenue.
In contrast, standard class tickets, which account for 91% of sales, contribute 80% of the revenue. 
This disparity highlights the premium pricing power of first class tickets and suggests strategic opportunities for revenue optimization.
##### Revenue Contribution Analysis: 
The revenue breakdown indicates that standard class tickets, which make up the majority of sales, are priced significantly lower than first class tickets. 
This substantial price differential underlines the premium value attributed to first class services, including added comfort, amenities, and exclusivity, which justify higher ticket prices.
##### First Class Revenue Efficiency: 
The fact that first class tickets contribute 20% to total revenue despite being only 9% of sales demonstrates their high revenue efficiency. 
Each first class ticket generates significantly more revenue compared to a standard class ticket.
This premium pricing strategy is effective in capitalizing on a smaller, more affluent customer base willing to pay extra for enhanced services.
##### Passenger Volume vs. Revenue: 
The high popularity of the Manchester Piccadilly to Liverpool Lime Street route indicates a strong demand for travel between these two major cities.
The frequent travel could be attributed to various factors such as business commutes, leisure trips, and the connectivity between key economic and cultural hubs. 
Despite this, the route's lower revenue generation highlights the prevalence of standard class ticket sales, which dominate in terms of volume but contribute less to overall revenue due to their lower price point.
###	On-Time Performance Diagnosis:
The dataset provides detailed information on train ticket sales, including journey status and reasons for delays, allowing for an in-depth analysis of on-time performance and contributing factors. 
With a focus on National Rail’s train journeys from January to April 2024, this analysis aims to diagnose issues affecting punctuality and suggest improvements.
Out of the 22 recorded transactions, the majority of journeys were completed on time, with only three instances of delays. 
This high rate of punctuality (approximately 86%) indicates overall efficient service. However, understanding the reasons behind the delayed journeys is crucial for further improving on-time performance.
##### Contributing Factors to Delays: 
The dataset identifies two main reasons for delays: signal failure and technical issues. Signal failure caused delays in two instances, while technical issues were responsible for one delay.
Each delay resulted in minor disruptions, but their causes are significant as they reflect areas where infrastructural and operational improvements could be made.
##### Downtime Analysis:
Weather conditions emerged as the most significant factor contributing to transit downtime, accounting for 677 hours and 15 minutes.
This substantial figure highlights the need for better weather-related contingency planning and infrastructure improvements to mitigate such delays. 
In contrast, traffic contributed the least to downtime, with only 46 hours and 54 minutes lost. This suggests that road traffic has a minimal impact on train punctuality, 
likely due to the independence of rail transport from road conditions.
##### Revenue Impact:
Delays and cancellations have led to a 5% revenue loss due to refunds.
This financial impact, though relatively small, indicates the importance of minimizing service disruptions to maintain revenue stability.

 ## RECOMMENDATIONS
##### 1.	Increase Morning and Evening Services:
 Given the high volumes of passengers during these times, it is recommended to increase train frequency and capacity in the morning and evening periods.
     Ensuring that there are enough trains to meet demand will help reduce overcrowding and improve passenger satisfaction
##### 2. 	Expand First Class Offerings:
 Given the high revenue contribution of first class tickets, there is potential to increase first class capacity or enhance the services offered to attract more customers.
Improving marketing efforts to highlight the benefits of first class travel could also drive higher sales in this segment.
##### 3.	Flexible Scheduling: 
Adjusting train schedules to cater to the afternoon and night travelers can optimize resource allocation. 
Introducing additional services during slightly less busy periods can distribute the passenger load more evenly throughout the day.
##### 4.	Infrastructure Upgrades:
Investing in better signalling systems and regular maintenance could mitigate the risk of signal failures. Up-to-date technology and fail-safes can significantly reduce such incidents.
##### 5.	Enhanced Weather Preparedness:
Investing in better weather forecasting tools and implementing robust weather response strategies, particularly for morning services, can reduce downtime caused by weather conditions.
##### 6.	Focus on Key Routes: 
Given that a significant proportion of refunds comes from routes involving London stations, targeted improvements on these routes could enhance reliability and customer satisfaction. 
This might include infrastructure upgrades, better resource allocation, and more rigorous monitoring and maintenance schedules.

## 🛠 Skills and Tools
Excel, Power query, DAX, Power BI, Problem solving, Critical thinking, Transport Management...


## Screenshots

![maven uk train](https://github.com/user-attachments/assets/01967083-d61f-4ea3-991c-6d97c615f566)

![Dashboard Screenshot]
![maven uk train_page-0001](https://github.com/user-attachments/assets/5b7e4125-2273-4de9-9e81-5493686c29ad)

## Features

- Dynamic DashBoard
- Raw Datasets

