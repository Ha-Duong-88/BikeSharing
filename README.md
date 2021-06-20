![Rides_per_Weekday](https://user-images.githubusercontent.com/80140082/122685596-33a0c680-d1c1-11eb-95a6-1512ef3007ce.png)
# BikeSharing

In your README markdown file, include the following:
Overview of the analysis: Explain the purpose of this analysis.
Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.
Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

# Project Overview
The objective of this project is to create an analysis to convince investers that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, bike trip analysis examined the New York City Bike Program to draw some conclusions and recommendations.

The project scope involved utilizing Jupyter Notebook and Python to import the NYC Citibike dataset of 2,344,224 rows of data and Pandas to change the "tripduration" column from an integer to a datetime datatype. The converted dataset was then imported into Tableau to perform the analysis. Tableau was used to create a function to convert the "gender" column from an integer to a string, a set of interactive visualizations to analyze the data, and dashboards and a storyboard to display the results and analysis.

# Results of Analysis
The following are the key findings:

1) Subscribers, or repeat bike riders, make up the largest proportion of the total New City Citi Bike user base. The total subscriber customer base is 4.3x larger than casual riders. Male riders make up the largest number of riders of 2,344,224. 

The following is the distribution:

         * Male riders make up 65% of the total customer base.
         * Female riders make up 25% of the total customer base.
         * Unknown gender type make up 10% of the total customer base.

![Customers and Gender Breakdown](https://user-images.githubusercontent.com/80140082/122685140-77460100-d1be-11eb-8ae0-6e6e8d058ae7.png)


2) Male subscribers have the longest total bike trip durations. Casual riders have the shortest trip durations and utilize the bike sharing service primarily on the weekends. 

![Avg_Trip_Duration](https://user-images.githubusercontent.com/80140082/122685481-757d3d00-d1c0-11eb-8241-fa2ecb10d98a.png)


3) The most popular weekday and hours for the highest number of bike trips are during commuter hours. Thursday is the busiest day of the week, followed by Friday and Saturdays. Casual riders primarily utilize the bike service during the weekends with Saturday having the highest number of bike rides. 

![Rides_per_Weekday](https://user-images.githubusercontent.com/80140082/122685600-3dc2c500-d1c1-11eb-97b5-3ad98c60fbb5.png)

![Commuters vs  Weekend Leisure Riders](https://user-images.githubusercontent.com/80140082/122685606-474c2d00-d1c1-11eb-8bea-8e5cbf910720.png)



# Summary
The size of the NYC Citi Bike Sharing ridership base in 2019 was 28% of the New York City population of 8.419M according to US Census 2019. For densely populated metropolitan areas, a bike sharing program has high potential for riders that want to make frequent and short bike trips and for casual riders interested in using the service for leisure or one-time trips.

Based on the analysis, there are several conclusions and recommendations.

1) Subscriber customers are responsible for more bike trips and longer trip duration over casual customers.
2) The highest number of bike rides and utilization is during the peak commuter hours from Monday - Friday with Thursday being the peak day.
3) Casual riders tend to utilize the bike sharing service more on Saturdays and Sundays. This is likely for leisure purposes and one-time trips to perform errands.

## Recommendations
1) Maximize the number of subscribers as they are repeat customers. Subscribers are more likely than casual customers to use the bike sharing program to commute to work or for work purposes, such as food delivery, messenger services or as an alternative, quicker mode of transportation for short trips rather than driving, walking or taking public transporation.

2) Since male riders comprise the highest number of users, conduct a deeper analysis to identify other dimensions about this user base such as profession and bike usage purposes. For example, if the purpose is to deliver food, determine the most popular locations in the city for food delivery and ensure that there are more bikes available for rental and pickup and drop-off points for those locales.

3) Further analyze the demographics of the 'Unknown' user type as this can sway the distribution of male vs. female vs. other riders that prefer not to self-identify due to personal reasons. 

4) Further analyze the profitability of subscribers vs. casual riders, male vs. famale vs. unknown user types, and trip durations. For casual riders, if the pricing model is by the hour, for example, identify opportunities to increase the average trip duration through special campaigns and promotions, particularly for leisure rentals. Assuming that the number of subscribers will remain relatively stable because these riders are using bikes for work commute purposes, there is a potential uplift opportunity in the casual customer base by advertising tourist-friendly ride packages, offering bike packages for family trips around the city, and building partnerships with other tourist services in the city.


## Link to Tableau Public for the charts and story board
https://public.tableau.com/app/profile/hd123/viz/Bike_Sharing_Challenge_16240678047710/NYCCitiBikeStory
